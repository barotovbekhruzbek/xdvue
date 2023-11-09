<template>
<div class="banner-1">
   <div class="container">
    <img src="../../../../assets/images/banner.png" alt="" class="banner-foto"> 
 </div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.banner-1 {
   @media(max-width:900px) {
      display: none;
   }
}

  .banner-foto {
   width: 1242px;
    height: 270px;
    @media(max-width:1152px) {
      width: 100%;
    }
  }
</style>