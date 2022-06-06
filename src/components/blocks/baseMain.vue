<template>
  <main>
    <upperMain />
  </main>
</template>

<script>
import upperMain from "../mainSections/upperMain.vue";
export default {
  name: "baseMain",
  components: {
    upperMain,
  },
};
</script>

<style lang="scss">
main {
  background-color: var(--mainpage-color);
}
</style>