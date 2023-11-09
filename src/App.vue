<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './layouts/Navbar.vue';
import Footer from './layouts/Footer.vue';

</script>

<template>

<div class="nav">
  <Navbar />
 
  <RouterView />
  <Footer />
</div>

</template>

<style lang="scss">
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
  @media(max-width:1252px) {
    max-width: 1100px;
  }
  @media(max-width:1100px){
    max-width: 900px;
  }
  @media(max-width:900px) {
    max-width: 700px;
  }
}
</style>
