<template>
  <footer>
    <div class="container">
      <div class="card">
        <div class="img_card">
          <img
            src="../assets/img/buy-comics-digital-comics.png"
            alt="Dc Digital Comics"
          />
        </div>
        <div class="card_description">Digital Comics</div>
      </div>
      <div class="card">
        <div class="img_card">
          <img
            src="../assets/img/buy-comics-merchandise.png"
            alt="Dc Merchandise"
          />
        </div>
        <div class="card_description">Dc Merchandise</div>
      </div>
      <div class="card">
        <div class="img_card">
          <img
            src="../assets/img/buy-comics-subscriptions.png"
            alt="Dc Subscriptions"
          />
        </div>
        <div class="card_description">Subscriptions</div>
      </div>
      <div class="card">
        <div class="img_card">
          <img
            src="../assets/img/buy-comics-shop-locator.png"
            alt="Dc Shop Locator"
          />
        </div>
        <div class="card_description">Comic Shop Locator</div>
      </div>
      <div class="card">
        <div class="img_card">
          <img
            src="../assets/img/buy-dc-power-visa.svg"
            alt="Dc Buy Power Visa"
          />
        </div>
        <div class="card_description">Dc Power Visa</div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
footer {
  padding: 2.8rem;
  background-color: var(--secondary-color);
  & .container {
    display: flex;
    justify-content: space-around;
    color: white;
    text-transform: uppercase;
  }
  .card {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 0.9rem;
  }

  .card img {
    max-width: 3rem;
    width: 100%;
  }
}
</style>