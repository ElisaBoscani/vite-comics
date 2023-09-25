<script>
import MainLink from "./MainLink.vue";
export default {
  name: "AppMain",
  data() {
    return {};
  },
  components: {
    MainLink,
  },
};
</script>

<template>
  <main>
    <section class="bg_top">
      <div class="p-3"></div>
    </section>
    <MainLink></MainLink>
  </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
section {
  height: 200px;
}

div {
  background-image: url("../assets/img/jumbotron.jpg");
  background-size: cover;
  height: 200px;
}
</style>
