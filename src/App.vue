<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://zone.eu/" target="_blank">
      <img src="../zone_profile_square.svg" class="logo" alt="Zone logo" />
    </a>
  </div>
  <HelloWorld msg="Hello World!" />
</template>

<style scoped>
.logo {
  width: 200px;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #EC0009);
}
</style>
