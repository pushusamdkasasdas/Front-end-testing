<template>
  <div id="app">
    <!-- <router-view /> -->
    <banner-one></banner-one>
    <banner-two></banner-two>
  </div>
</template>

<script>
import BannerOne from "./components/BannerOne.vue";
import BannerTwo from "./components/BannerTwo.vue";
export default {
  components: { BannerOne, BannerTwo },
  name: "App",
};
</script>

BannerOne
<style lang="scss" scoped>
#app {
  display: flex;
  flex-direction: row;
}
</style>
