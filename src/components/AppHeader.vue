<script>
export default {
  name: "App",
  data() {
    return {
      activeNav: 0,
      navElement: [
        { text: "Character" },
        { text: "Comics" },
        { text: "Movies" },
        { text: "Tv" },
        { text: "Games" },
        { text: "Collectibles" },
        { text: "Videos" },
        { text: "Fans" },
        { text: "News" },
        { text: "Shop" },
      ],
    };
  },
  methods: {
    select(index) {
      this.activeNav = index;
    },
  },
};
</script>

<template>
  <header>
    <nav class="navbar s">
      <div class="d-flex align-items-center p-2 container">
        <div>
          <img src="../assets/img/dc-logo.png" alt="" />
        </div>
        <div class="d-inline">
          <a
            class="navbar-brand text-uppercase fw-bold d-inline"
            href="#"
            v-for="(elem, index) in navElement"
            :class="index === activeNav ? 'active' : ''"
            @click="select(index)"
          >
            {{ elem.text }}</a
          >
          <!--  <a class="navbar-brand fw-bold active" href="#">COMICS</a>
          <a class="navbar-brand fw-bold" href="#">MOVIES</a>
          <a class="navbar-brand fw-bold" href="#">TV</a>
          <a class="navbar-brand fw-bold" href="#">GAMES</a>
          <a class="navbar-brand fw-bold" href="#">COLLECTIBLES</a>
          <a class="navbar-brand fw-bold" href="#">VIDEOS</a>
          <a class="navbar-brand fw-bold" href="#">FANS</a>
          <a class="navbar-brand fw-bold" href="#">NEWS</a>
          <a class="navbar-brand fw-bold" href="#">SHOP</a> -->
        </div>
      </div>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
.active {
  border-bottom: 2px solid #0282f9;
  color: #0282f9;
}
a {
  font-size: $font-size-base;
}
</style>
