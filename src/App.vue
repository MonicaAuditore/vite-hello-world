<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    AppTitle,
    AppHero,
  },
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<template>
  <!-- <AppTitle /> -->
  <AppHero />
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>
