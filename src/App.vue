<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './layouts/Navbar.vue';

</script>

<template>

<div class="nav">
  <Navbar />
  <RouterView />
</div>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Inter', sans-serif;
}
.container {
  max-width: 1242px;
  margin: 0 auto;
}
</style>
