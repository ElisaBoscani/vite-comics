<script></script>

<template>
  <div class="footer_botton">
    <div class="d-flex justify-content-between container p-3">
      <div class="border border-2 border-primary p-2">
        <a href="#" class="text-uppercase fw-bolder"> Sing-up now!</a>
      </div>
      <div class="d-flex justify-content-evenly w-50 align-items-center">
        <a href="#" class="follow fs-5 text-uppercase fw-bolder">Follow us</a>
        <img src="../assets/img/footer-facebook.png" alt="" />
        <img src="../assets/img/footer-twitter.png" alt="" />
        <img src="../assets/img/footer-youtube.png" alt="" />
        <img src="../assets/img/footer-pinterest.png" alt="" />
        <img src="../assets/img/footer-periscope.png" alt="" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
.footer_botton {
  background-color: $comics_footer;
}
.footer_botton img {
  width: 25px;
}
.follow {
  color: $comics_secondary;
}
</style>
