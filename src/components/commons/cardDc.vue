<template>
  <div class="dcCard">
    <div class="imgCard">
      <img :src="thumb" :alt="series" />
    </div>
    <h4>{{ title }}</h4>
  </div>
</template>

<script>
export default {
  name: "cardDc",
  props: {
    title: String,
    thumb: String,
    series: String,
  },
};
</script>

<style lang="scss">
.dcCard img {
  width: 100%;
}

.imgCard {
  max-height: 11.25rem;
  overflow: hidden;
}
</style>