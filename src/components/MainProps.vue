<script>
export default {
  name: "MainProps",
  props: {
    thumb: String,
    price: String,
    series: String,
    type: String,
  },
};
</script>

<template>
  <!--   <div class="d-flex col col-md-6">
    <div class="card">
      <img :src="thumb" alt="" />
      <h3>{{ series }}</h3>
    </div>
  </div> -->
  <div class="col">
    <div class="card bg_card border-0" style="width: 10rem">
      <img :src="thumb" class="card-img-top" alt="..." />
      <div class="">
        <h3 class="fs-5 text-white">{{ series }}</h3>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
img {
  height: 60%;
}
.bg_card {
  background-color: $comics_footer;
}
</style>
