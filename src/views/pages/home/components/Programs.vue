<template>
    <div class="carusel-mobile">
     <div class="container">
       <div class="carusel-title">
          
           <h3> <i><svg width="25" height="15" viewBox="0 0 25 15" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M18.524 3.5162C16.5525 3.37299 14.5388 3.29718 12.4996 3.29718C10.4605 3.29718 8.45522 3.37299 6.47532 3.5162C6.25533 3.53304 6.0438 3.54989 5.84073 3.56674L3.81006 12.8413C6.20456 11.8725 10.1982 13.1866 12.5081 14.8377C14.818 13.1866 18.8116 11.8725 21.2062 12.8413L19.1755 3.56674C18.9555 3.54989 18.744 3.53304 18.524 3.5162ZM19.3616 11.2492C19.1755 11.2913 18.9893 11.1734 18.9555 10.9965L17.7286 5.41154C17.6948 5.23463 17.8132 5.04932 17.9909 5.01562C18.1686 4.9735 18.3548 5.09143 18.3971 5.26833L19.607 10.8533C19.6578 11.0302 19.5393 11.2155 19.3616 11.2492Z" fill="#1C345A"/>
<path d="M20.1909 1.17089C19.8105 1.05296 19.4385 0.943455 19.0496 0.842373C17.0037 0.303249 14.7972 0 12.5061 0C10.215 0 8.01696 0.294827 5.96261 0.842373C3.84907 1.38992 1.90463 2.21544 0.196894 3.25156C0.0531743 3.32737 -0.0313668 3.46215 0.0109036 3.59694C0.0531743 3.79068 0.298344 3.90861 0.543514 3.86649C2.50487 3.57166 4.49159 3.35265 6.49522 3.20102C8.47348 3.05781 10.4771 2.982 12.5146 2.982C14.552 2.982 16.5641 3.05781 18.5339 3.20102C19.4977 3.27684 20.4445 3.36106 21.3914 3.47058C21.1631 2.62821 20.8503 1.90376 20.4361 1.44888L20.1909 1.17089Z" fill="#1C345A"/>
<path d="M24.8284 3.26842C24.0366 2.78826 23.1858 2.35023 22.3013 1.96274C22.3602 2.08067 22.4192 2.20702 22.4529 2.33338C22.5961 2.72088 22.7056 3.17576 22.773 3.63064C23.3374 3.70645 23.8933 3.78226 24.4577 3.8665C24.6178 3.88335 24.7863 3.84966 24.8958 3.74015C25.0558 3.59695 25.0305 3.38634 24.8284 3.26842Z" fill="#1C345A"/>
<path d="M22.5288 8.42373C22.6046 8.42373 22.6636 8.44057 22.7225 8.45743C22.7815 6.07351 22.6635 3.66432 22.2002 2.42603C21.7622 1.21301 21.0462 1.08666 20.625 1.26355C21.7706 2.53554 22.1244 5.34064 22.3182 8.46586C22.3856 8.44057 22.4614 8.42373 22.5288 8.42373Z" fill="#1C345A"/>
<path d="M22.529 9.7464C22.3521 9.7464 22.192 9.67058 22.0741 9.54422C21.9899 9.75482 21.9478 9.99068 21.9478 10.235C21.9478 10.7994 22.1836 11.2879 22.529 11.5069C22.866 11.2795 23.1102 10.7909 23.1102 10.235C23.1102 9.99068 23.0681 9.75482 22.9755 9.54422C22.8744 9.67058 22.7059 9.7464 22.529 9.7464Z" fill="#1C345A"/>
<path d="M22.1162 9.10065C22.1162 9.32808 22.2931 9.51342 22.529 9.51342C22.7564 9.51342 22.9417 9.31968 22.9417 9.10065C22.9417 8.8732 22.7564 8.68789 22.529 8.68789C22.3015 8.67946 22.1162 8.8732 22.1162 9.10065Z" fill="#1C345A"/>
</svg>
</i> Programs | 52,300</h3>
       </div>
       <Splide :options="options">
         <SplideSlide v-for="item of 8" :key="item.id">
          <div class="programs-box">
            <div class="programs-title">
                <h3>MSc Health
Research Methods</h3>
            </div>
            <div class="program-universty">
                <div class="logo-program">
                    <img src="../../../../assets/images/oxford.png" alt="">
                </div>
                <div class="logo-program-title">
                    <p>Heriot-Watt
University Malaysia</p>
                </div>
            </div>
            <div class="bottom-program">    
                <h3>UK</h3>
                <h3>$ 25,000</h3>
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

   .programs-box {
    padding: 8px;
    width: 189px;
    height: 140px;
    border-radius: 15px;
    background: #FFF;

    box-shadow: 0px 3px 3px 0px rgba(0, 0, 0, 0.16);
   }
   .programs-title h3{
    width: 160px;
    color: #203456;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        padding: 8px;
        border-bottom:0.5px solid #BCBCBC;

   }
   .program-universty {
    padding-top: 5px;
    padding-bottom: 5px;
    display: flex;
    align-items: center;
    gap:8px;
    border-bottom: 0.5px solid #BCBCBC;
   }
   .logo-program-title p {
    color: #203456;
    font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: normal;
   }
   .bottom-program{
    padding-top: 8px;
    display: flex;
    justify-content: space-between;
    align-items: center;
   }
   .bottom-program h3 {
    color: #606060;
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
   }

   </style>