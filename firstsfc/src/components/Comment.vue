<template>
  <div class="comments">
    <h1>Comments</h1>

    <ul v-if="comments.length">
      <li v-for="comment in comments" :key="comment.id">
        <strong>{{ comment.name }}</strong>: {{ comment.comment }}
      </li>
    </ul>

    <p v-else>No comments yet.</p>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import { supabase } from '../lib/supabaseClient'

const comments = ref([])

async function getComments() {
  const { data, error } = await supabase.from('comments').select()
  if (!error) comments.value = data
}

onMounted(getComments)

// expose so parent can refresh after submit
defineExpose({ getComments })
</script>

<style scoped>
.comments {
  border: dashed black 1px;
  margin: 10px;
  padding: 10px;
  background-color: lightyellow;
}
</style>
