<template>
  <div id="app">
    <baseHeader />
    <baseMain />
  </div>
</template>

<script>
import baseHeader from "./components/baseHeader.vue";
import baseMain from "./components/baseMain.vue";

export default {
  name: "App",
  components: {
    baseHeader,
    baseMain,
  },
};
</script>

<style lang="scss">
@import "./assets/style/global.scss";
</style>