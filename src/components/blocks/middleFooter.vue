<template>
  <div class="middleFooter">
    <div class="container">
      <div class="col-left">
        <div class="footNav">
          <h2>Dc Comics</h2>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </div>
        <div class="footNav">
          <h2>Shop</h2>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
      </div>
      <div class="col-left">
        <div class="footNav">
          <h2>Dc</h2>
          <ul>
            <li><a href="#">Terms of use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
      </div>
      <div class="col-left">
        <div class="footNav">
          <h2>Sites</h2>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <div class="col-right">
        <img src="../../assets/img/dc-logo-bg.png" alt="Dc Logo" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.middleFooter {
  background-image: url("../../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  height: 21.875rem;
  overflow: hidden;
  .col-left {
    width: calc(50% / 3);
  }
  .col-right {
    width: 50%;
    overflow: hidden;
    display: flex;
    justify-content: flex-end;
  }

  ul {
    list-style: none;
  }

  ul li a {
    color: var(--footer-color);
    text-decoration: none;
    font-size: 0.875rem;
  }

  ul li a:hover {
    color: var(--secondary-color);
  }
  .col-right img {
    width: 31rem;
    object-position: 0 -6.25rem;
  }
}
</style>