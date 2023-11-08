<template>
 <div>
  <search />
  <banner />
  <carusel />
 </div>
</template>

<script>
import Banner from './components/Banner.vue'
import Carusel from './components/Carusel.vue'
import Search from './components/Search.vue'
export default {
  components: { Search, Banner, Carusel },

}
</script>

<style scoped>
  div {
    background: #F5F5F5;
  }
</style>