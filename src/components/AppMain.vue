<script>
import MainLink from "../components/MainLink.vue";
/* import MainProps from "../components/MainProps.vue"; */
import product from "../product.js";
export default {
  name: "AppMain",
  data() {
    return {
      product: comic,
    };
  },
  components: {
    MainLink,
    product,
  },
};
</script>

<template>
  <main>
    <section class="bg_top img_jumb">
      <div class="p-3"></div>
    </section>
    <MainLink> </MainLink>
  </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
.img_jumb {
  background-image: url(../assets/img/jumbotron.jpg);
  background-position: top;
  background-size: cover;
  background-repeat: no-repeat;
  padding: 140px;
}
</style>
