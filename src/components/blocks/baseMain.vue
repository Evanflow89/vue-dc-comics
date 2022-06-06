<template>
  <main>
    <upperMain />
    <bottomMain />
  </main>
</template>

<script>
import upperMain from "../mainSections/upperMain.vue";
import bottomMain from "../mainSections/bottomMain.vue";
export default {
  name: "baseMain",
  components: {
    upperMain,
    bottomMain,
  },
};
</script>

<style lang="scss">
main {
  background-color: var(--mainpage-color);
}
</style>