<script setup>
import navigation from "./components/navbar.vue";
import heading from "./components/header.vue";
import content from "./components/content.vue";
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
