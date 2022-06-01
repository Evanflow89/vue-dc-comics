<template>
  <header>
    <div class="container">
      <div class="imgLogo">
        <img src="../assets/img/dc-logo.png" alt="dc Logo" />
      </div>
      <nav class="mainNav">
        <ul>
          <li
            v-for="(link, index) in links"
            :key="index"
            :class="{ active: link.current }"
          >
            <a :href="link.url">{{ link.text }}</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "baseHeader",
  data() {
    return {
      links: [
        {
          text: "Characters",
          url: "#",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: true,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "Tv",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss">
header {
  background-color: white;
  display: flex;
  flex-direction: row;
  & .container {
    height: 7.75rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  & .imgLogo img {
    max-width: 5rem;
    width: 100%;
  }
  & nav ul {
    display: flex;
    gap: 1.5rem;
    list-style: none;
  }

  nav ul li a {
    color: var(--primary-color);
    text-decoration: none;
    text-transform: uppercase;
    font-weight: 600;
    font-size: 1rem;
  }
  & .active a {
    color: var(--secondary-color);
    border-bottom: 0.375rem solid var(--secondary-color);
  }
}
</style>