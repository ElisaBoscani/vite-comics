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
  <div>
    <img :src="thumb" alt="" />
    <h3>{{ serie }}</h3>
  </div>
</template>
