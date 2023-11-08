<template>
 <div>
  <search />
  <banner />
  <carusel />
  <CaruselAdventure/>
  <Banner2Vue />
 </div>
</template>

<script>
import Banner from './components/Banner.vue'
import Carusel from './components/Carusel.vue'
import Search from './components/Search.vue'
import CaruselAdventure from './components/Carusel-adventure.vue'

import Banner2Vue from './components/Banner2.vue'
export default {
  components: { Search, Banner, Carusel , CaruselAdventure,Banner2Vue},

}
</script>

<style scoped>
  div {
    background: #F5F5F5;
  }
</style>