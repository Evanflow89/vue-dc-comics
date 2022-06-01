<template>
  <div id="app">
    <baseHeader />
  </div>
</template>

<script>
import baseHeader from "./components/baseHeader.vue";

export default {
  name: "App",
  components: {
    baseHeader,
  },
};
</script>

<style lang="scss">
@import "./assets/style/global.scss";
</style>