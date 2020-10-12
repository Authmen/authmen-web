<template>
  <div id="app">
    <Header />
    <Hero />
    <MainPart />
  </div>
</template>

<script>
// components
import Header from "./components/Header.vue";
import Hero from "./components/Hero.vue";
import MainPart from "./components/MainPart.vue";

export default {
  name: "app",
  components: {
    Header,
    Hero,
    MainPart
  }
};
</script>

<!-- add common style-->
<style lang="less">
@import "./styles/main.module.less";
</style>
