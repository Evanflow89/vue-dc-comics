<template>
  <div class="dcCard">
    <img :src="thumb" :alt="series" />
  </div>
</template>

<script>
export default {
  name: "cardDc",
  props: {
    thumb: String,
    series: String,
  },
};
</script>

<style>
</style>