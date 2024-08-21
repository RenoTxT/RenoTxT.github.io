<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container-fluid nav-space">
    <navigation/>
  </div>
  <div class="container-fluid">
    <!-- <heading/> -->
    <content/>
  </div>
</template>

<style scoped>
*{
  background-color: black;
}

.nav-space{
  margin-bottom: 15vh;
}
</style>
