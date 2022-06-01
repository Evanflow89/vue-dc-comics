<template>
  <div id="app">
    <baseHeader />
    <baseMain />
    <topFooter />
  </div>
</template>

<script>
import baseHeader from "./components/baseHeader.vue";
import baseMain from "./components/baseMain.vue";
import topFooter from "./components/topFooter.vue";

export default {
  name: "App",
  components: {
    baseHeader,
    baseMain,
    topFooter,
  },
};
</script>

<style lang="scss">
@import "./assets/style/global.scss";
</style>