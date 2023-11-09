<template>
  <div class="cards-advanture">
    <div class="container">
        <div class="title-advar">
            <h2>Your Unique Adventure</h2>
        </div>
       <div class="card-advanture">
        <div class="left" v-for="card of 2" :key="card.id">
            <div class="box-1" v-for="item of 2" :key="item.id">
                <div class="left-box-logo">
                    <img src="../../../../assets/images/card1.png" alt="">
                </div>
                <div class="left-box-logo-title">
                    <h3>Study Destinations</h3>
                    <p>Find your own ideal
                study destination</p>
                </div>
            </div>
        </div>
       </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import url("../../../../styles/components/advanture.scss");
</style>