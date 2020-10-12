<template>
  <div class="header clearfix">
    <a href="/" class="logo">
      <img src="../assets/logo.png" alt="" />
    </a>
    <div class="nav float-right">
      <ul>
        <li><a href="#authmen">Home</a></li>
        <li><a href="#technology">Technology</a></li>
        <!-- <li><a href="#team">Team</a></li> -->
        <li><a href="#roadmap">Road Map</a></li>
        <!-- <li><a href="#updates">Updates</a></li> -->
      </ul>
      <!-- <a href="" class="download">Download Whitepaper</a> -->
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.header {
  height: 66px;
  padding: 0 16% 0 72px;
  background: rgba(12, 12, 12, 0.82);
  line-height: 66px;
  position: fixed;
  left: 0;
  right: 0;
  z-index: 11;
  .logo {
    display: inline-block;
    img {
      position: absolute;
      bottom: 26%;
      height: 30px;
    }
  }
  .nav {
    display: inline-block;
    a {
      font-size: 15px;
      font-family: Lato;
      font-weight: 400;
      color: rgba(246, 246, 246, 1);
      text-decoration: none;
    }
    ul {
      display: inline-block;
      > li {
        display: inline-block;
        padding: 0 16px;
      }
    }
    .download {
      display: inline-block;
      height: 28px;
      padding: 2px 12px;
      border: 1px solid rgba(179, 179, 179, 1);
      line-height: 28px;
      margin-left: 12px;
    }
  }
}
@media screen and (max-width: 768px) {
  .header {
    padding: 0 16px;
    box-sizing: border-box;
    width: 100%;
    height: 66px;
    .nav {
      display: none;
    }
  }
}
</style>
