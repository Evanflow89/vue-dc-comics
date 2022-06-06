<template>
  <div class="dcCard">
    <img :src="thumb" :alt="series" />
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
</style>