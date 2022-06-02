<template>
  <div class="footerBottom">
    <div class="container foot">
      <div class="btn_foot"></div>
      <div class="social_foot">
        <div class="icon">
          <img src="../assets/img/footer-facebook.png" alt="facebook logo" />
        </div>
        <div class="icon">
          <img src="../assets/img/footer-twitter.png" alt="twitter logo" />
        </div>
        <div class="icon">
          <img src="../assets/img/footer-youtube.png" alt="youtube logo" />
        </div>
        <div class="icon">
          <img src="../assets/img/footer-pinterest.png" alt="pinterest logo" />
        </div>
        <div class="icon">
          <img src="../assets/img/footer-periscope.png" alt="periscope logo" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.footerBottom {
  background-color: var(--primary-color);
}

.container.foot {
  height: 7rem;
  justify-content: space-between;
  align-items: center;
}

.social_foot {
  display: flex;
  gap: 1rem;
}
</style>