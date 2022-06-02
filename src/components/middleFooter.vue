<template>
  <div class="middleFooter">
    <div class="container">
      <div class="col-left"></div>
      <div class="col-left"></div>
      <div class="col-left"></div>
      <div class="col-right"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.middleFooter {
  background-image: url("../assets/img/footer-bg.jpg");
  &.container {
  }
  .col-left {
    width: 20%;
  }
  .col-right {
    width: 40%;
  }
}
</style>