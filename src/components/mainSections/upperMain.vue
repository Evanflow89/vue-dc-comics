<template>
  <main>
    <div class="jumbo_img">
      <img src="../../assets/img/jumbotron.jpg" alt="jumbo image" />
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss">
main {
  .jumbo_img img {
    width: 100%;
    max-height: 19rem;
    object-fit: cover;
    object-position: center top;
  }
}
</style>