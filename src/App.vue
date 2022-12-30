<script setup>
  import Banner from './components/Banner.vue'
  import Navbar from './components/Navbar.vue'
</script>

<template>
  <Navbar />
  <div class="banner">
    <Banner msg="Grimnomicon" />
  </div>
</template>

<style scoped>
.banner {
  margin: 0;
  display: flex;
  place-items: center;
  min-width: 320px;
  min-height: 100vh;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
