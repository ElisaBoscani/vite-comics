<script></script>

<template>
  <main>
    <section class="bg_top">
      <div class="p-3 container">
        <h3>Content goes here</h3>
      </div>
    </section>
    <section class="bg_botton">
      <div
        class="p-5 container d-flex justify-content-between align-items-center"
      >
        <div>
          <img
            src="../assets/img/buy-comics-digital-comics.png"
            alt=""
            class="pe-2"
          />
          <span class="text-white text-uppercase">Digital Comics</span>
        </div>
        <div>
          <img
            src="../assets/img/buy-comics-merchandise.png"
            alt=""
            class="pe-2"
          />
          <span class="text-white text-uppercase">Dc Merchandise</span>
        </div>
        <div>
          <img
            src="../assets/img/buy-comics-subscriptions.png"
            alt=""
            class="pe-2"
          />
          <span class="text-white text-uppercase">Subscription</span>
        </div>
        <div>
          <img
            src="../assets/img/buy-comics-shop-locator.png"
            alt=""
            class="pe-2 w_img"
          />
          <span class="text-white text-uppercase">Comic shop locator</span>
        </div>
        <div>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" class="pe-2" />
          <span class="text-white text-uppercase">Dc Power Visa</span>
        </div>
      </div>
    </section>
  </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
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
