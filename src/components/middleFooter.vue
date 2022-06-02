<template>
  <div class="middleFooter">
    <div class="container">
      <div class="col-left"></div>
      <div class="col-left"></div>
      <div class="col-left"></div>
      <div class="col-right">
        <img src="../assets/img/dc-logo-bg.png" alt="Dc Logo" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.middleFooter {
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  .container {
    display: flex;
  }
  .col-left {
    width: calc(50% / 3);
  }
  .col-right {
    width: 50%;
    position: relative;
    overflow: hidden;
  }
  .col-right img {
    object-fit: none;
    object-position: -1.875rem -6rem;
  }
}
</style>