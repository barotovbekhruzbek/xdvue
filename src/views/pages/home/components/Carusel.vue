<template>
   <div class="container">
    <div class="carusel-title">
        <h2>Explore Top Study Destinations</h2>
        <h3>Discover study destinations in more than 120 diverse countries.</h3>
    </div>
    <Splide :options="options">
      <SplideSlide v-for="item of 8" :key="item.id">
        <div class="box-carusel">
            <div class="box-img">
                <img src="../../../../assets/images/carusel.png" alt="Sample 1">
            </div>
            <div class="box-title">
                <h4>Study Destinations</h4>
                <p>Find your own ideal <br>
                study destination</p>
            </div>
        </div>
      </SplideSlide>
 
    </Splide>
   </div>
  </template>
  
  
  <script>
  import { Splide, SplideSlide } from '@splidejs/vue-splide';
  import { defineComponent } from 'vue';
  
  
  export default defineComponent( {
    components: {
      Splide,
      SplideSlide,
    },
  
  
    setup() {
      const options = {
        rewind: true,
        gap   : '110px',
        perPage: 3,
      };
  
  
      return { options };
    },
  } );
  </script>
  <style>
@import '@splidejs/splide/dist/css/splide.min.css';

.carusel-title {
  padding-top: 38px;

}
.carusel-title h2 {
  color: #1C345A;

  
  font-size: 30px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.carusel-title h3 {
  color: #1C345A;
  
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  padding-bottom: 10px;
}

.box-carusel {
  width: 434px;
  height: 290px;
  background: #fff;

  border-radius: 10px;
  background: #FFF;

  box-shadow: 0px 3px 3px 0px rgba(0, 0, 0, 0.16);
}
.box-title {
  padding-top: 8px;
padding-left: 11px;
  
}
.box-title h4 {
  color: #1C345A;
font-size: 20px;
font-style: normal;
font-weight: 400;
line-height: normal;
}
.box-title p {
  padding-top: 20px;
  color: #606060;
  
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

</style>