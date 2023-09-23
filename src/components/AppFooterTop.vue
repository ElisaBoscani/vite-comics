<script></script>

<template>
  <div class="margin_top">
    <div class="d-flex justify-content-between bg_img">
      <div class="d-flex gap-5 container col p-4 marg_top_col">
        <!-- comisc -->
        <div>
          <div>
            <h3 class="text-white text-uppercase">DC Comics</h3>
            <ul class="p-0">
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
          </div>
          <!-- shop -->
          <div>
            <h3 class="text-white text-uppercase">Sites</h3>
            <ul class="p-0">
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
        </div>
        <!-- dc -->
        <div>
          <h3 class="text-white text-uppercase">DC</h3>
          <ul class="p-0">
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy Policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <!-- sites -->
        <div>
          <h3 class="text-white text-uppercase">Sites</h3>
          <ul class="p-0">
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universal</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>

      <div class="col pb-4 img_logo"></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
.bg_img {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
}
.img_logo {
  background-image: url(../assets/img/dc-logo-bg.png);
  background-position: center;
  background-repeat: no-repeat;
}
.margin_top {
  margin-top: -13px;
}

li {
  list-style-type: none;
}

h3 {
  font-size: 20px;
}
</style>
