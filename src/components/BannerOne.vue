<template>
  <div class="banner-one">
    <div class="navbar">
      <div class="navbar_container">
        <div class="log"></div>
        <div class="nav">
          <ul>
            <li>
              <a href="#">我的课程</a>
            </li>
            <li>
              <a href="#">关于我们</a>
            </li>
            <li>
              <a href="#">新闻资讯</a>
            </li>
            <li>
              <a href="#">比赛</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="background"></div>
    <div class="first_card">
      <div class="top">
        <div class="first_card_dot">
          <span class="first_card_fristdot"></span>
          <span class="first_card_senconddot"></span>
          <span class="first_card_thirddot"></span>
        </div>
        <p>粉老鼠</p>
      </div>
      <div class="center">
        <div class="center_left">
          <img src="../assets//pinkmouse.png" alt="" />
        </div>
        <div class="center_right"></div>
      </div>
    </div>

    <div class="second_card">
      <div class="top">
        <div class="second_card_dot">
          <span class="second_card_fristdot"></span>
          <span class="second_card_senconddot"></span>
          <span class="second_card_thirddot"></span>
        </div>
        <p>粉老鼠</p>
      </div>
      <div class="center">
        <div class="center_left">
          <img src="../assets//pinkmouse.png" alt="" />
        </div>
        <div class="center_right"></div>
      </div>
    </div>

    <div class="third_card">
      <div class="top">
        <div class="third_card_dot">
          <span class="third_card_fristdot"></span>
          <span class="third_card_senconddot"></span>
          <span class="third_card_thirddot"></span>
        </div>
        <p>热气球</p>
      </div>
      <div class="center">
        <div class="center_left">
          <img src="../assets//pinkmouse.png" alt="" />
        </div>
        <div class="center_right"></div>
      </div>
    </div>

    <div class="shade_top"></div>
    <div class="shade_bottom"></div>
  </div>
</template>

<script>
import gsap from "gsap";
export default {
  mounted() {
    // gsap.to(".background", { duration: 1, x: 800, delay: 2 });
  },
};
</script>

<style lang="scss" scoped>
* {
  margin: 0 auto;
  padding: 0;
}
li {
  list-style: none;
}
a {
  text-decoration: none;
  color: #333;
}
.banner-one {
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
  .navbar_container {
    position: fixed;
    left: 40px;
    top: 21px;
    width: 1120px;
    height: 49px;
    opacity: 1;
    z-index: 3;
    .log {
      float: left;
      width: 128px;
      height: 49px;
      background: url(../assets/logo.png);
    }
    .nav {
      float: right;
      width: 399px;
      height: 25px;
      ul {
        display: flex;
        li {
          height: 49px;
          line-height: 49px;
          font-weight: bold;
        }
      }
    }
  }
  .background {
    position: absolute;
    left: 191px;
    top: 371px;
    width: 615px;
    height: 310.04px;
    background: url(../assets/ads.png);
  }
  .first_card {
    position: absolute;
    left: 965px;
    top: -224px;
    width: 800px;
    height: 460px;
    border-radius: 18px;
    background: rgba(255, 255, 255, 1);
    box-shadow: 0px 1px 5px rgba(110, 110, 110, 0.3);
    .top {
      margin: 0 20px;
      width: 760px;
      height: 46px;
      font-size: 24px;
      font-weight: 600;
      line-height: 46px;
      text-align: center;
      color: rgba(0, 0, 0, 1);
      .first_card_dot {
        float: left;
        height: 46px;
        .first_card_fristdot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(237, 105, 94, 1);
        }
        .first_card_senconddot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(227, 179, 74, 1);
        }
        .first_card_thirddot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(97, 197, 85, 1);
        }
      }
      p {
        float: left;
        margin-left: 278px;
      }
    }
    .center {
      margin: 0 20px 20px;
      width: 760px;
      height: 394px;
      opacity: 1;
      border-radius: 12px;
      background: rgba(252, 250, 245, 0.8);
      .center_left {
        float: left;
        width: 270px;
        height: 394px;
        border-radius: 12px 0px 0px 12px;
        background: rgba(220, 253, 254, 1);
        img {
          margin: 80px 29px 86px 28px;
        }
      }
    }
  }

  .second_card {
    position: absolute;
    left: 965px;
    top: 296px;
    width: 800px;
    height: 460px;
    opacity: 1;
    border-radius: 18px;
    background: rgba(255, 255, 255, 1);
    box-shadow: 0px 1px 5px rgba(110, 110, 110, 0.3);
    .top {
      margin: 0 20px;
      width: 760px;
      height: 46px;
      font-size: 24px;
      font-weight: 600;
      line-height: 46px;
      text-align: center;
      color: rgba(0, 0, 0, 1);
      .second_card_dot {
        float: left;
        height: 46px;
        .second_card_fristdot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(237, 105, 94, 1);
        }
        .second_card_senconddot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(227, 179, 74, 1);
        }
        .second_card_thirddot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(97, 197, 85, 1);
        }
      }
      p {
        float: left;
        margin-left: 278px;
      }
    }

    .center {
      margin: 0 20px 20px;
      width: 760px;
      height: 394px;
      opacity: 1;
      border-radius: 12px;
      background: rgba(252, 250, 245, 0.8);
      .center_left {
        float: left;
        width: 270px;
        height: 394px;
        border-radius: 12px 0px 0px 12px;
        background: rgba(255, 125, 163, 0.2);
        img {
          margin: 80px 29px 86px 28px;
        }
      }
      .center_right {
      }
    }
  }
  .third_card {
    position: absolute;
    left: 965px;
    top: 816px;
    width: 800px;
    height: 460px;
    opacity: 1;
    border-radius: 18px;
    background: rgba(255, 255, 255, 1);
    box-shadow: 0px 1px 5px rgba(110, 110, 110, 0.3);
    .top {
      margin: 0 20px;
      width: 760px;
      height: 46px;
      font-size: 24px;
      font-weight: 600;
      line-height: 46px;
      text-align: center;
      color: rgba(0, 0, 0, 1);
      .third_card_dot {
        float: left;
        height: 46px;
        .third_card_fristdot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(237, 105, 94, 1);
        }
        .third_card_senconddot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(227, 179, 74, 1);
        }
        .third_card_thirddot {
          float: left;
          display: block;
          margin: 18px 6px 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background: rgba(97, 197, 85, 1);
        }
      }
      p {
        float: left;
        margin-left: 278px;
      }
    }
    .center {
      margin: 0 20px 20px;
      width: 760px;
      height: 394px;
      opacity: 1;
      border-radius: 12px;
      background: rgba(252, 250, 245, 0.8);
      .center_left {
        float: left;
        width: 270px;
        height: 394px;
        border-radius: 12px 0px 0px 12px;
        background: rgba(225, 221, 244, 1);
        img {
          margin: 80px 29px 86px 28px;
        }
      }
    }
  }
  .shade_bottom {
    position: fixed;
    left: 920px;
    top: 912px;
    width: 996px;
    height: 168px;
    background: linear-gradient(
      rgba(255, 255, 255, 1) 0%,
      rgba(255, 255, 255, 0) 100%
    );
  }
  .shade_top {
    position: fixed;
    left: 925px;
    top: 0px;
    width: 996px;
    height: 168px;
    background: linear-gradient(
      180deg,
      rgba(255, 255, 255, 1) 0%,
      rgba(255, 255, 255, 0) 100%
    );
    z-index: 2;
  }
}
</style>
