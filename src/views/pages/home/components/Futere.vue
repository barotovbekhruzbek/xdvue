<template>
    <div class="carusel-mobile">
     <div class="container">
       <div class="carusel-title">
           <h2>Design Your Future</h2>
           <h3> <i><svg width="25" height="20" viewBox="0 0 25 20" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M5.63348 7.08406V6.25924C5.63348 6.16851 5.5345 6.08603 5.40253 6.08603H2.75488C2.63115 6.08603 2.52393 6.16026 2.52393 6.25924V7.08406C2.52393 7.17479 2.62291 7.25726 2.75488 7.25726H2.88685L2.72188 15.159H2.54867V15.5879H5.55925V15.159H5.42728L5.26231 7.25726H5.39428C5.52625 7.25726 5.63348 7.18303 5.63348 7.08406Z" fill="#1C345A"/>
<path d="M14.1901 7.08406V6.25924C14.1901 6.16851 14.0911 6.08603 13.9592 6.08603H11.3115C11.1878 6.08603 11.0806 6.16026 11.0806 6.25924V7.08406C11.0806 7.17479 11.1796 7.25726 11.3115 7.25726H11.4435L11.2785 15.159H11.1053V15.5879H14.1159V15.159H13.9839L13.819 7.25726H13.9509C14.0911 7.25726 14.1901 7.18303 14.1901 7.08406Z" fill="#1C345A"/>
<path d="M22.7482 7.08406V6.25924C22.7482 6.16851 22.641 6.08603 22.5173 6.08603H19.8696C19.7459 6.08603 19.6387 6.16026 19.6387 6.25924V7.08406C19.6387 7.17479 19.7377 7.25726 19.8696 7.25726H20.0016L19.8366 15.159H19.6634V15.5879H22.674V15.159H22.542L22.3771 7.25726H22.509C22.641 7.25726 22.7482 7.18303 22.7482 7.08406Z" fill="#1C345A"/>
<rect x="1.72412" y="15.7356" width="21.7667" height="1" fill="#1C345A"/>
<rect x="1.6084" y="4.56525" width="21.7667" height="1" fill="#1C345A"/>
<rect x="0.849609" y="16.8656" width="23.3504" height="1" fill="#1C345A"/>
<rect y="18.0203" width="25" height="1" fill="#1C345A"/>
<path d="M21.1491 2.98995L14.3545 0.28456C13.391 -0.0948534 11.8276 -0.0948534 10.8726 0.28456L4.06948 2.98995H0.849609V3.9055H24.2V2.98995H21.1491ZM12.6389 2.75901C12.1741 2.75901 11.7938 2.38784 11.7938 1.93419C11.7938 1.48054 12.1741 1.10937 12.6389 1.10937C13.1037 1.10937 13.484 1.48054 13.484 1.93419C13.484 2.38784 13.1037 2.75901 12.6389 2.75901Z" fill="#1C345A"/>
</svg>
</i> University Rankings | 36,582</h3>
       </div>
       <Splide :options="options">
         <SplideSlide v-for="item of 8" :key="item.id">
          <div class="box-mobile">
            <div class="top-mobile-box">
                <div class="box-logo">
                    <img src="../../../../assets/images/oxford.png" alt="">
                </div>
                <div class="box-logo-title">
                    <p>Local # 1 | Global # 1</p>
                    <p>Top University</p>
                </div>
            </div>
            <div class="bottom-mobile-box">
                <h3>Heriot-Watt
University Malaysia</h3>
<p>United States of America </p>
<h5>Recognized in Jordan</h5>
            </div>
          </div>
         </SplideSlide>
    
       </Splide>
      </div>
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
           breakpoints: {
             1152:{
               perPage: 2,
               gap   : '1px',
             },
             900:{
               perPage: 2,
               gap   : '20px',
             }
           }  
         };
         
     
     
         return { options };
       },
     } );
     </script>
     <style>
   @import '@splidejs/splide/dist/css/splide.min.css';
     .carusel-mobile {
        display: none;
     }
     @media(max-width:670px){
        .carusel-mobile {
            display: block;
        }
     }
   
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
   .box-mobile {
    padding: 8px;
    width: 189px;
    height: 139px;
    background: #fff;
    border-radius: 15px;
    background: #FFF;

    box-shadow: 0px 3px 3px 0px rgba(0, 0, 0, 0.16);
   }
   .top-mobile-box {
    display: flex;
    align-items: center;
    gap: 6px;
    padding-bottom: 8px;
    border-bottom: 0.5px solid #BCBCBC;
   }
   .box-logo-title {
    color: #203456;

  
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
   }
   .bottom-mobile-box h3 {
    color: #203456;

    width: 147px;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
   }
   .bottom-mobile-box p{
    /* 91 448 35 44 */
    color: #606060;

font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: normal;
border-bottom: 0.5px solid #BCBCBC;
   }
   .bottom-mobile-box h5 {
    color: #007A00;

    padding-top: 5px;
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
   }

   </style>