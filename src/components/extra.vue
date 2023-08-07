<template>
  <div class="extra">
    <div class="red"></div>
  </div>
</template>

<script>
import { gsap } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";

gsap.registerPlugin(ScrollTrigger);
export default {
  mounted() {
    ScrollTrigger.create({
      trigger: ".extra",
      start: "top top",
      scrub: true,
      end: "+=2000",
      pin: true,
      animation: gsap.to(".red", {
        x: 200,
        y: 500,
        rotation: 180,
      }),
    });
  },
};
</script>

<style lang="scss" scoped>
.extra {
  height: 1080px;
  width: 1920px;
  .red {
    width: 400px;
    height: 400px;
    background-color: red;
  }
}
</style>
