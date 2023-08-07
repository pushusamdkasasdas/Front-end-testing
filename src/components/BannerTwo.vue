<template>
  <div class="banner-two">
    <div class="rectangle-orange"></div>
    <div class="round-gary"></div>
    <div class="rectangle-left"></div>
    <div class="round-orange"></div>
    <div class="round-bottom"></div>
    <div class="rectangle-gary"></div>
    <div class="triangle"></div>
    <div class="path"></div>
    <div class="shade"></div>
    <div class="text">
      <p class="text-time">第三届（2022-2023学年）</p>
      <div class="text-content">
        <p>全国青少年科技</p>
        <p>教育成果展示大赛</p>
      </div>
      <div class="text-name"># GOC编程挑战赛 #</div>
      <div class="more">
        <span class="more-text">探索更多</span>
        <span class="toMore"></span>
      </div>
    </div>
    <div class="people"></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.banner-two {
  overflow: hidden;
  position: relative;
  width: 1920px;
  height: 1080px;
  background: linear-gradient(
    127.59deg,
    rgba(255, 240, 240, 1) 0%,
    rgba(255, 255, 255, 1) 21.92%,
    rgba(255, 255, 255, 1) 71.61%,
    rgba(249, 240, 243, 1) 100%
  );

  .rectangle-orange {
    position: absolute;
    left: 144.75px;
    top: 267px;
    width: 57.5px;
    height: 57.5px;
    border-radius: 4px;
    transform: rotate(56.11deg);
    background: rgba(236, 112, 0, 1);
    z-index: 2;
  }
  .round-gary {
    position: absolute;
    left: 370px;
    top: 47px;
    width: 96px;
    height: 96px;
    border-radius: 50%;
    background: rgba(49, 106, 218, 0.22);
    z-index: 2;
  }
  .round-orange {
    position: absolute;
    left: 1141px;
    top: 11px;
    width: 19px;
    height: 19px;
    border-radius: 50%;
    background: rgba(236, 112, 0, 0.5);
    z-index: 2;
  }

  .rectangle-gary {
    position: absolute;
    left: 1238.96px;
    top: 30px;
    width: 36.33px;
    height: 36.33px;
    transform: rotate(57.14deg);
    background: rgba(49, 106, 218, 0.2);
    z-index: 2;
  }
  .rectangle-left {
    position: absolute;
    left: 404px;
    top: 890.68px;
    width: 54.88px;
    height: 54.88px;
    border-radius: 4px;
    transform: rotate(-24.41deg);
    background: rgba(241, 180, 30, 0.2);
    z-index: 2;
  }
  .round-bottom {
    position: absolute;
    width: 51px;
    height: 51px;
    left: 130px;
    top: 890px;
    border-radius: 50%;
    background: rgba(165, 214, 63, 0.5);
    z-index: 2;
  }
  .triangle {
    position: absolute;
    left: 895px;
    top: 780.32px;
    width: 89.47px;
    height: 89.47px;
    // transform: rotate(100.51deg);
    background: url(../assets/yellowtriangle.png) no-repeat;
    z-index: 3;
  }
  .path {
    position: absolute;
    left: 893.65px;
    top: -41.41px;
    width: 1097.35px;
    height: 1182.08px;
    background: url(../assets/path.png) no-repeat center / cover;
    z-index: 2;
  }
  .shade {
    position: absolute;
    left: 0px;
    top: 0px;
    width: 1920px;
    height: 1080px;
    background: linear-gradient(
      127.59deg,
      rgba(255, 240, 240, 1) 0%,
      rgba(255, 255, 255, 1) 21.92%,
      rgba(255, 255, 255, 1) 71.61%,
      rgba(249, 240, 243, 1) 100%
    );
  }
  .text {
    position: absolute;
    left: 240px;
    top: 326px;
    width: 567px;
    height: 386.5px;
    z-index: 2;
    .text-time {
      left: 240px;
      top: 326px;
      margin: 0;
      width: 370px;
      height: 80px;
      /** 文本1 */
      font-size: 30px;
      font-weight: 400;
      letter-spacing: 0px;
      line-height: 80px;
      color: rgba(128, 128, 128, 1);
      text-align: left;
      vertical-align: top;
    }
    .text-content {
      width: 576px;
      height: 160px;
      /** 文本1 */
      font-size: 72px;
      font-weight: 500;
      letter-spacing: 0px;
      line-height: 80px;
      font-family: 阿里巴巴普惠体;
      background: linear-gradient(
        to right,
        rgba(51, 106, 218, 1) 0%,
        rgba(127, 154, 235, 1) 11%,
        rgba(112, 112, 203, 1) 22.38%,
        rgba(254, 147, 132, 1) 64.83%,
        rgba(249, 216, 73, 1) 100%
      );
      background-clip: text;
      color: transparent;
      text-align: left;
      p {
        margin: 0;
      }
    }
    .text-name {
      margin-top: 32px;
      width: 217px;
      height: 47px;
      border-radius: 50px;
      background: rgba(245, 245, 245, 1);
      font-size: 20px;
      font-weight: 400;
      letter-spacing: 0px;
      text-align: center;
      line-height: 47px;
    }
    .more {
      margin-top: 31px;
      width: 168px;
      height: 45px;
      font-weight: 700;
      .more-text {
        float: left;
        height: 45px;
        display: block;
        line-height: 45px;
      }
      .toMore {
        position: relative;
        float: left;
        display: block;
        margin-left: 12px;
        width: 80px;
        height: 45px;
        background: url(../assets/tomore.png) no-repeat center 100%;
        &::after {
          content: "";
          display: block;
          position: absolute;
          left: -50px;
          background: white;
          width: 80px;
          height: 45px;
          opacity: 50%;
          transform: rotate(-45deg);
        }
        &:hover::after {
          left: 120%;
          transition: all 600ms cubic-bezier(0.3, 1, 0.2, 1);
          -webkit-transition: all 600ms cubic-bezier(0.3, 1, 0.2, 1);
        }
      }
    }
  }
  .people {
    position: absolute;
    left: 990px;
    top: 336px;
    width: 893px;
    height: 437px;
    background: url(../assets/people.png) no-repeat;
    z-index: 3;
  }
}
</style>
