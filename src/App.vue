<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooterTop from "./components/AppFooterTop.vue";
import AppFooterBottom from "./components/AppFooterBottom.vue";
import product from "./product.js";
export default {
  name: "App",
  data() {
    return {};
  },
  components: {
    AppHeader,
    AppMain,
    AppFooterTop,
    AppFooterBottom,
  },
};
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <footer>
    <AppFooterTop></AppFooterTop>
    <AppFooterBottom></AppFooterBottom>
  </footer>
</template>

<style lang="scss">
@use "./assets/scss/partials/variables" as *;
</style>
