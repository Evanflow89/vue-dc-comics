<template>
  <div id="app">
    <baseHeader />
    <baseMain />
    <topFooter />
    <middleFooter />
    <bottomFooter />
  </div>
</template>

<script>
import baseHeader from "./components/baseHeader.vue";
import baseMain from "./components/baseMain.vue";
import topFooter from "./components/topFooter.vue";
import middleFooter from "./components/middleFooter.vue";
import bottomFooter from "./components/bottomFooter.vue";

export default {
  name: "App",
  components: {
    baseHeader,
    baseMain,
    topFooter,
    middleFooter,
    bottomFooter,
  },
};
</script>

<style lang="scss">
@import "./assets/style/global.scss";
</style>