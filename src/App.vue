<script setup>
import HelloWorld from './components/HelloWorld.vue'
import EjemploBoostrapVue  from './components/EjemploBoostrapVue.vue';
</script>

<template>
  <h1 class="text-center">Bootstrap Vue</h1>
  <EjemploBoostrapVue/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
