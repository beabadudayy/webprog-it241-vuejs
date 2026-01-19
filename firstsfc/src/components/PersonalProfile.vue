<template>
  <div class="container">
    <header><h1>Personal Profile Web page</h1></header>
    <main>
      <section class="main-content">
        <div>1 About Me</div>
        <div>2 Education / Achievements</div>
        <div>3 Course</div>
        <div>4 IT Experience</div>
        <div>5 Hobbies & Interests</div>
        <div>6 Goals In Life / Dream</div>
        <div>7 Picture Gallery</div>
      </section>
      <aside class="sidebar"></aside>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
.container {
  font-family: Arial, sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

header h1 {
  text-align: center;
}

.main-content div {
  padding: 10px;
  border-bottom: 1px solid #ccc;
}

.sidebar {
  background-color: #f4f4f4;
  padding: 15px;
  margin-top: 20px;
}
</style>