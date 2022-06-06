<template>
  <div class="footerBottom">
    <div class="container foot">
      <div class="btn_foot">
        <button class="signUp">Sign-up now!</button>
      </div>
      <div class="social_foot">
        <div class="follow">
          <h3>Follow Us</h3>
        </div>
        <div class="icon">
          <img src="../../assets/img/footer-facebook.png" alt="facebook logo" />
        </div>
        <div class="icon">
          <img src="../../assets/img/footer-twitter.png" alt="twitter logo" />
        </div>
        <div class="icon">
          <img src="../../assets/img/footer-youtube.png" alt="youtube logo" />
        </div>
        <div class="icon">
          <img
            src="../../assets/img/footer-pinterest.png"
            alt="pinterest logo"
          />
        </div>
        <div class="icon">
          <img
            src="../../assets/img/footer-periscope.png"
            alt="periscope logo"
          />
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
  align-items: center;
  gap: 1.25rem;
}

.signUp {
  background-color: var(--primary-color);
  color: white;
  border: 0.125rem solid var(--secondary-color);
  text-transform: uppercase;
  padding: 0.625rem;
  font-size: 1rem;
}

.signUp:hover {
  background-color: var(--secondary-color);
}
</style>