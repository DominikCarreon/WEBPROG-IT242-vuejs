<template>
  <div class="comment-form">
    <h2>Leave a Comment</h2>

    <form @submit.prevent="submitComment">
      <div class="form-group">
        <label>Name</label>
        <input v-model="name" required />
      </div>

      <div class="form-group">
        <label>Comment</label>
        <textarea v-model="comment" required></textarea>
      </div>

      <button type="submit">Submit</button>
      <p v-if="submissionStatus">{{ submissionStatus }}</p>
    </form>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import { supabase } from '../lib/supabaseClient'

const emit = defineEmits(['submitted'])

const name = ref('')
const comment = ref('')
const submissionStatus = ref('')

async function submitComment() {
  submissionStatus.value = 'Submitting...'

  const { error } = await supabase
    .from('comments')
    .insert([{ name: name.value, comment: comment.value }])

  if (error) {
    submissionStatus.value = 'Error submitting comment'
  } else {
    submissionStatus.value = 'Comment submitted!'
    name.value = ''
    comment.value = ''
    emit('submitted') // 🔥 tell parent to refresh list
  }
}
</script>

<style scoped>
.comment-form {
  margin: 10px;
}

.form-group {
  margin-bottom: 10px;
}
</style>
