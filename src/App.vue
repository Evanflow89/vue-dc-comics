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
import baseHeader from "./components/blocks/baseHeader.vue";
import baseMain from "./components/blocks/baseMain.vue";
import topFooter from "./components/blocks/topFooter.vue";
import middleFooter from "./components/blocks/middleFooter.vue";
import bottomFooter from "./components/blocks/bottomFooter.vue";

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