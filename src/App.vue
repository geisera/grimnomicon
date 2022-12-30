<script setup>
  import Banner from './components/Banner.vue'
  import Navbar from './components/Navbar.vue'
</script>

<template>
    <Navbar />
    <Banner class="banner" msg="Grimnomicon2" />
</template>

<style scoped>
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
