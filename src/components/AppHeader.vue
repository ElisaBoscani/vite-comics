<script></script>

<template>
  <header>
    <nav class="navbar s">
      <div class="d-flex align-items-center p-2 container w-100">
        <div>
          <img src="../assets/img/dc-logo.png" alt="" />
        </div>
        <div class="">
          <a class="navbar-brand fw-bold" href="#">CHARACTERS</a>
          <a class="navbar-brand fw-bold active" href="#">COMICS</a>
          <a class="navbar-brand fw-bold" href="#">MOVIES</a>
          <a class="navbar-brand fw-bold" href="#">TV</a>
          <a class="navbar-brand fw-bold" href="#">GAMES</a>
          <a class="navbar-brand fw-bold" href="#">COLLECTIBLES</a>
          <a class="navbar-brand fw-bold" href="#">VIDEOS</a>
          <a class="navbar-brand fw-bold" href="#">FANS</a>
          <a class="navbar-brand fw-bold" href="#">NEWS</a>
          <a class="navbar-brand fw-bold" href="#">SHOP</a>
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
