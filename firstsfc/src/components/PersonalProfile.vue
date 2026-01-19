<template>
  <div class="profile-page">
    <h1>Personal Profile Web Page</h1>

    <section>
      <h2>About Me</h2>
      <p>Education / Achievements</p>
      <p>Senior high school at Asia Pacific College</p>
      <p><strong>Course:</strong> BS Information Technology</p>
      <p><strong>IT Experience:</strong> HTML, CSS, Java, Python</p>
      <p><strong>Hobbies and Interests:</strong> Eating and drinking coffee</p>
      <p><strong>Goals In Life:</strong> To be happy and rich</p>
    </section>

    <section>
      <h2>Picture Gallery</h2>
      <img
        src="https://via.placeholder.com/500x600"
        alt="Profile picture"
      />
    </section>

    <div class="grid-container">
      <header class="header">
        <h1>Dominik Personal Profile</h1>
      </header>

      <nav class="menu">
        <ul>
          <li>LinkedIn</li>
          <li>Facebook</li>
          <li>Instagram</li>
        </ul>
      </nav>

      <main class="content">
        <h2>About Me</h2>
        <p>Dominik nickname is Doms.</p>
        <p>Doms finishes requirements on time.</p>
        <p>Doms likes coffee.</p>
      </main>

      <aside class="facts">
        <h2>Facts</h2>
        <ul>
          <li>I like reading books</li>
          <li>I study for long hours</li>
        </ul>
      </aside>

      <footer class="footer">
        <p>© 2025 Dominik Profile</p>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: "PersonalProfile"
};
</script>

<style scoped>
.profile-page {
  padding: 20px;
  font-family: Arial, sans-serif;
}

.grid-container {
  display: grid;
  grid-template-areas:
    "header header"
    "menu content"
    "menu facts"
    "footer footer";
  grid-gap: 10px;
}

.header { grid-area: header; background: #eee; padding: 10px; }
.menu { grid-area: menu; background: #ddd; padding: 10px; }
.content { grid-area: content; background: #f5f5f5; padding: 10px; }
.facts { grid-area: facts; background: #f0f0f0; padding: 10px; }
.footer { grid-area: footer; background: #ccc; padding: 10px; text-align: center; }

img {
  max-width: 100%;
}
</style>
