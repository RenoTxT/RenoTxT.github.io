<script setup>
import navbar from "./components/navbar.vue";
import headerer from "./components/header.vue";
import content from "./components/content.vue";

</script>

<template>
  <main>
    <navbar />
  </main>
  <header>
    <headerer />
  </header>
  <section>
    <content/>
  </section>
</template>

<style scoped>
*{
  background-color: black;
}
</style>
