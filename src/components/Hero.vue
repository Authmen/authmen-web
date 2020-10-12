<template>
  <div>
    <div class="hero">
      <div class="center-area">
        <div class="title-bg"></div>
        <div class="title">
          <p>
            Authmen
          </p>
          <h1>Trusted Blockchain Storage Protocol</h1>
          <a href="">
            <!-- <img src="../assets/misc/icon_intro_download@2x.png" alt="" /> -->
            <!-- Download Whitepaper -->
          </a>
        </div>
      </div>
    </div>
    <div id="authmen" class="features">
      <Tabs />
    </div>
  </div>
</template>

<script>
import Tabs from "./Tabs.vue";
export default {
  name: "Hero",
  components: {
    Tabs
  },
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.hero {
  height: 771px;
  position: relative;
  background: url("../assets/bg/img_title_bg.jpeg");
  background-size: cover;
  .title-bg {
    width: 476px;
    height: 418px;
    background: rgba(222, 0, 0, 1);
    position: absolute;
    bottom: 140px;
    mix-blend-mode: multiply;
    z-index: 1;
  }
  .title {
    width: 476px;
    height: 418px;
    position: absolute;
    bottom: 140px;
    padding: 0 18px 0 24px;
    z-index: 1;
    box-sizing: border-box;
    &:before {
      content: "";
      position: absolute;
      width: 84px;
      height: 2px;
      background: rgba(255, 255, 255, 1);
      top: 40px;
    }
    h1 {
      font-family: Lato-Black;
      font-weight: 900;
      margin-top: 12px;
      // width: 400px;
      display: wrap;
      font-size: 36px;
      color: #f6f6f6;
      line-height: 54px;
    }
    p {
      font-family: Lato;
      font-weight: 400;
      color: #f6f6f6;
      line-height: 24px;
      margin-top: 180px;
    }
    a {
      position: absolute;
      bottom: 0;
      display: block;
      font-size: 18px;
      font-family: Lato;
      font-weight: bold;
      color: rgba(246, 246, 246, 1);
      line-height: 24px;
      padding: 20px 0;
      text-decoration: none;
      img {
        width: 24px;
        height: 24px;
        margin-right: 10px;
        vertical-align: middle;
      }
    }
  }
  &:after {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    height: 204px;
    background: rgba(242, 242, 242, 1);
    background-image: url("../assets/bg/img_decoration_bg@2x.png");
    background-size: 36px;
  }
}
.features {
  position: relative;
  &::after {
    content: "";
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    height: 130px;
    background: linear-gradient(to bottom, transparent 0%, #ffffff 100%);
  }
}
@media screen and (max-width: 768px) {
  .hero {
    width: 100%;
    background-position-x: 40%;
    .title-bg,
    .title {
      padding: 0 16px;
      box-sizing: border-box;
      margin: 0 auto;
      width: 92.5%;
      height: 418px;
      p {
        margin-top: 172px;
        font-size: 14px;
        font-family: Lato;
        font-weight: 400;
        color: rgba(246, 246, 246, 1);
        line-height: 24px;
      }
      h1 {
        margin-top: 12px;
        width: 100%;
        height: auto;
        font-size: 36px;
        font-family: Lato-Black, Lato;
        font-weight: 900;
        color: #f6f6f6;
        line-height: 54px;
      }
      a {
        img {
          width: 18px;
          height: 18px;
        }
      }
    }
  }
}
</style>
