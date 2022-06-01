<template>
  <main>
    <div class="container">
      <div class="content">&lt;--Content Goes Here--&gt;</div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss">
main {
  background-color: var(--mainpage-color);

  & .container {
    height: 7.75rem;
    width: 100%;
    display: flex;
    align-items: center;
    color: white;
    font-weight: 600;
    font-size: 1.75rem;
  }
}
</style>