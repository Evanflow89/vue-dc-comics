<template>
  <header>
    <div class="container">
      <div class="imgLogo">
        <img src="../assets/img/dc-logo.png" alt="dc Logo" />
      </div>
      <nav class="mainNav">
        <ul>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
          <li>
            <a href="#">Link</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "baseHeader",
};
</script>

<style lang="scss">
header {
  background-color: white;
  display: flex;
  flex-direction: row;
  & .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  & nav ul {
    display: flex;
    gap: 1.5rem;
    list-style: none;
  }

  & nav ul li a {
    color: var(--primary-color);
    text-decoration: none;
    text-transform: uppercase;
  }
}
</style>