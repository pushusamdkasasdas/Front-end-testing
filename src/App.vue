<template>
  <div id="app">
    <!-- <router-view /> -->
    <banner-one></banner-one>
    <banner-two></banner-two>
    <extra></extra>
  </div>
</template>

<script>
import BannerOne from "./components/BannerOne.vue";
import BannerTwo from "./components/BannerTwo.vue";
import extra from "./components/extra.vue";
export default {
  components: { BannerOne, BannerTwo, extra },
  name: "App",
};
</script>

BannerOne
<style lang="scss" scoped>
/* #app {
  display: flex;
  flex-direction: row;
} */
</style>
