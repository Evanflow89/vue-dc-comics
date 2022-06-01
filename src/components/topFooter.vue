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