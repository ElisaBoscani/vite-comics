<script>
import MainLink from "./MainLink.vue";
export default {
  name: "AppMain",
  data() {
    return {};
    components: {
      MainLink;
    }
  },
};
</script>

<template>
  <main>
    <section class="bg_top">
      <div class="p-3 container">
        <h3>Content goes here</h3>
      </div>
    </section>
    <MainLink></MainLink>
  </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
section {
  position: relative;

  z-index: 2;
}
.bg_top {
  background-color: $comics_primary;
  color: white;
  height: 120px;
}
.bg_botton {
  background-color: $comics_secondary;
}
img {
  width: 45px;
}
.w_img {
  width: 40px;
}
span {
  font-size: $font-size-base;
}
</style>
