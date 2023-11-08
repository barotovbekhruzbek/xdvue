<template>
    <div class="container">
     <div class="carusel-title">
         <h2>Your Unique Adventure</h2>
         
     </div>
     <Splide :options="options">
       <SplideSlide>
         <div class="box-carusel">
             <div class="box-img">
                 <img src="../../../../assets/images/card1.png" alt="Sample 1">
             </div>
             <div class="box-title">
                 <h4>Unlocking the Secrets</h4>
                 <p>to a Successful Study
Abroad Experience</p>
             </div>
         </div>
       </SplideSlide>
       <SplideSlide>
         <div class="box-carusel">
             <div class="box-img">
                 <img src="../../../../assets/images/card2.png" alt="Sample 1">
             </div>
             <div class="box-title">
                 <h4>Get Inspired</h4>
              <p>Essential Tips for
Choosing the Right
University and Major</p>
             </div>
         </div>
       </SplideSlide>
       <SplideSlide>
         <div class="box-carusel">
             <div class="box-img">
                 <img src="../../../../assets/images/card3.png" alt="Sample 1">
             </div>
             <div class="box-title">
                 <h4>Top Articles</h4>
                <p>Stay updated with
our fascinating
news and articles.</p>
             </div>
         </div>
       </SplideSlide>
       <SplideSlide>
         <div class="box-carusel">
             <div class="box-img">
                 <img src="../../../../assets/images/card4.png" alt="Sample 1">
             </div>
             <div class="box-title">
                 <h4>Top Universities</h4>
               <p>Stay updated with
our fascinating
news and articles.</p>
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
         perPage: 4,
       };
   
   
       return { options };
     },
   } );
   </script>
   <style lang="scss" scoped>
 @import '@splidejs/splide/dist/css/splide.min.css';
 
 .carusel-title {
   padding-top: 38px;
   padding-bottom: 25px;
 
 }
 .carusel-title h2 {
   color: #1C345A;
 
   
   font-size: 30px;
   font-style: normal;
   font-weight: 400;
   line-height: normal;
 }
.box-img{
    width: 331px;
    height: 187px;
}
.box-img img {
    width: 100%;
    height: 100%;
}
 
 .box-carusel {
   
    width: 331px;
    height: 325px;
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
    width: 138px;
   padding-top: 20px;
   color: #606060;
   
   font-size: 16px;
   font-style: normal;
   font-weight: 400;
   line-height: normal;
 }
 
 </style>