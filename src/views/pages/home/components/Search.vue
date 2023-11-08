<template>
  <div class="search-panel">
    <div class="container">
        <div class="search-input">
            <label for="where"> {{ where.length ==!0 ? labelof : label1 }} </label>
            <input type="text" v-model="where"  placeholder="Select study destination">
            <label for="where">Where?</label>
            <input type="text" placeholder="Select study destination">
            <label for="where">Where?</label>
            <input type="text" placeholder="Select study destination">
            <button>Search</button>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            where:"",
            label1: "Where?",
            labelof:""
        }
    }
}
</script>

<style lang="scss" scoped>
    @import url("../../../../styles/components/search.scss");
</style>