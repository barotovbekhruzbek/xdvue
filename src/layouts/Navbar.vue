<template>
  <header>
    <div class="container">
   <div class="desktop">
    <div class="nav">
            <div class="logo">
                <img src="../assets/images/logo.svg" alt="">
            </div>
            <div class="menu-link">
                <ul>
                    <li><a href="">Programs</a></li>
                    <li><a href="">Institutions</a></li>
                    <li><a href="">Agents</a></li>
                    <li><a href="">Rankings</a></li>
                </ul>
                <router-link to="" class="log">Log in</router-link>
                <router-link to="" class="sign">Sign Up</router-link>
            </div>
        </div>
        <div class="nav-bottom">
            <div class="title">
                <h1>Discover Your Perfect Study Path</h1>
                <h2>Explore Levels, Destinations, and Programs</h2>
            </div>
            <div class="title-bottom">
                <i class="fa-regular fa-waveform-lines"></i>
                <!-- <img src="../assets/images/icons.svg" alt=""> -->
                 <p> Filter my Preferences</p>
            </div>
        </div>
   </div>
   <div class="mobile">
    <div class="top">
        <div class="time">
        {{ new Date().getHours()  }}: {{ new Date().getMinutes() }}
    </div>
    <div class="icons">
        <i><svg width="18" height="12" viewBox="0 0 18 12" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M16.6667 11.3335H15.6668C15.1155 11.3335 14.6669 10.885 14.6669 10.3336V1.66664C14.6669 1.11529 15.1155 0.666744 15.6668 0.666744H16.6667C17.2181 0.666744 17.6666 1.11529 17.6666 1.66664V10.3336C17.6666 10.885 17.2181 11.3335 16.6667 11.3335ZM12.0002 11.3335H10.9994C10.4481 11.3335 9.9995 10.885 9.9995 10.3336V4.00034C9.9995 3.44899 10.4481 3.00044 10.9994 3.00044H12.0002C12.5516 3.00044 13.0001 3.44899 13.0001 4.00034V10.3336C13.0001 10.885 12.5516 11.3335 12.0002 11.3335ZM7.3328 11.3335H6.3329C5.78155 11.3335 5.333 10.885 5.333 10.3336V6.33314C5.333 5.78179 5.78155 5.33324 6.3329 5.33324H7.3328C7.88464 5.33324 8.3336 5.78179 8.3336 6.33314V10.3336C8.3336 10.885 7.88464 11.3335 7.3328 11.3335ZM2.6663 11.3335H1.6664C1.11505 11.3335 0.666504 10.885 0.666504 10.3336V8.33384C0.666504 7.782 1.11505 7.33304 1.6664 7.33304H2.6663C3.21765 7.33304 3.6662 7.782 3.6662 8.33384V10.3336C3.6662 10.885 3.21765 11.3335 2.6663 11.3335Z" fill="white"/>
</svg>
</i>
<i><svg width="16" height="12" viewBox="0 0 16 12" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M8.33037 11.2964C8.24768 11.2964 8.167 11.2626 8.10896 11.2037L6.11097 9.18765C6.04969 9.12727 6.01556 9.04329 6.01736 8.95725C6.01916 8.87137 6.05688 8.78904 6.12086 8.73135C6.73766 8.20944 7.52234 7.92203 8.33037 7.92203C9.1384 7.92203 9.92307 8.20945 10.5399 8.73135C10.6038 8.78821 10.6416 8.87054 10.6434 8.95725C10.6452 9.04329 10.611 9.12727 10.5498 9.18765L8.55176 11.2037C8.49289 11.2634 8.41426 11.2964 8.33037 11.2964ZM11.8386 7.75845C11.7586 7.75845 11.6825 7.7284 11.6244 7.67385C10.72 6.85495 9.55015 6.40395 8.33037 6.40395C7.11142 6.40395 5.94255 6.85494 5.03906 7.67385C4.98094 7.7284 4.90486 7.75845 4.82486 7.75845C4.74188 7.75845 4.66389 7.72617 4.60527 7.66755L3.45147 6.50115C3.38963 6.4393 3.35607 6.35748 3.35697 6.27075C3.35786 6.18389 3.39269 6.10271 3.45507 6.04215C4.78456 4.80537 6.51629 4.12425 8.33126 4.12425C10.1462 4.12425 11.878 4.80537 13.2075 6.04215C13.2704 6.10329 13.3056 6.18447 13.3065 6.27075C13.3074 6.35589 13.2732 6.43986 13.2129 6.50115L12.0582 7.66755C11.9995 7.72617 11.9216 7.75845 11.8386 7.75845ZM14.4981 5.07375C14.4171 5.07375 14.3411 5.04275 14.2839 4.98645C12.6689 3.45253 10.5546 2.60775 8.33037 2.60775C6.10524 2.60775 3.99091 3.45252 2.37687 4.98645C2.31969 5.04274 2.24361 5.07375 2.16267 5.07375C2.07968 5.07375 2.00169 5.04147 1.94307 4.98285L0.787465 3.81645C0.726215 3.7543 0.692975 3.67311 0.693865 3.58785C0.694765 3.50131 0.728965 3.42044 0.790165 3.36015C2.8283 1.40661 5.50611 0.330751 8.33037 0.330751C11.1546 0.330751 13.8324 1.40661 15.8706 3.36015C15.9312 3.42079 15.966 3.50378 15.966 3.58785C15.9669 3.67311 15.9336 3.7543 15.8724 3.81645L14.7168 4.98285C14.6581 5.04147 14.5805 5.07375 14.4981 5.07375Z" fill="white"/>
</svg>
</i>
<i>
    <svg width="25" height="12" viewBox="0 0 25 12" fill="none" xmlns="http://www.w3.org/2000/svg">
<path opacity="0.35" d="M0.5 3.00008C0.5 1.80346 1.47005 0.833412 2.66667 0.833412H19.3333C20.53 0.833412 21.5 1.80346 21.5 3.00008V9.00008C21.5 10.1967 20.53 11.1667 19.3333 11.1667H2.66667C1.47005 11.1667 0.5 10.1967 0.5 9.00008V3.00008Z" stroke="black"/>
<path opacity="0.4" d="M23 4.00008V8.00008C23.8047 7.6613 24.328 6.87321 24.328 6.00008C24.328 5.12694 23.8047 4.33885 23 4.00008Z" fill="black"/>
<path d="M2 3.66675C2 2.93037 2.59695 2.33341 3.33333 2.33341H18.6667C19.403 2.33341 20 2.93037 20 3.66675V8.33341C20 9.06979 19.403 9.66675 18.6667 9.66675H3.33333C2.59695 9.66675 2 9.06979 2 8.33341V3.66675Z" fill="black"/>
</svg>

</i>
    </div>
    
    </div>
    <div class="bottom">
        <div class="logo-2">
            <img src="../assets/images/logo2.svg" alt="">
        </div>
        <div class="search-mobile">
            <input type="text" placeholder="Find Course and Institutions">
            <i class="fas fa-search"></i>
        </div>
</div>
   </div>
    </div>
  </header>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    @import url("../styles/layout-style/navbar.scss");
</style>