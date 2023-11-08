<template>
  <header>
    <div class="container">
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
                <img src="../assets/images/icons.svg" alt="">
                 <p> Filter my Preferences</p>
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