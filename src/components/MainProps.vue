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

  <div class="card bg_card" style="width: 18rem">
    <img :src="thumb" class="card-img-top" alt="..." />
    <div class="card-body">
      <h3 class="fs-5">{{ series }}</h3>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
img {
  height: 100%;
}
</style>
