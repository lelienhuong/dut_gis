<template>
  <!-- <div class="navbar--wrapper">
    <b-navbar toggleable="lg">
      <b-navbar-brand href="#">
        <img src="../../../src/assets/logo-text.svg" alt="logo-text"
      /></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#" class="my-auto"> Trang chủ </b-nav-item>
          <b-nav-item href="#" class="my-auto">Tính năng</b-nav-item>
          <b-nav-item href="#" class="my-auto">Đối tượng sử dụng</b-nav-item>
          <b-nav-item href="#" class="my-auto">Q&A</b-nav-item>
          <b-nav-item href="#" class="my-auto">Thông tin liên hệ</b-nav-item>
        </b-navbar-nav>

      </b-collapse>
    </b-navbar>
  </div> -->
  <div class="navbar--wrapper">
    <b-navbar
      toggleable="lg"
      type="dark"
      variant="dark"
      class="py-3 navbar-custom"
    >
      <b-navbar-brand href="#">NavBar</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#" class="my-auto"> Trang chủ </b-nav-item>
          <b-nav-item href="#" class="my-auto">Tính năng</b-nav-item>
          <b-nav-item href="#" class="my-auto">Đối tượng sử dụng</b-nav-item>
          <b-nav-item href="#" class="my-auto">Q&A</b-nav-item>
          <b-nav-item href="#" class="my-auto">Thông tin liên hệ</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
.navbar--wrapper {
  width: 100%;
  position: absolute;
  z-index: 1300;
}
.navbar {
  height: auto;
}
.navbar.navbar-dark.bg-dark {
  background-color: #aabb55 !important;
  color: black;
}
.navbar-dark .navbar-nav .nav-link {
  color: black !important;
}
.navbar-brand {
  color: black !important;
}
.navbar-toggler-icon {
  background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'><path stroke='rgba(61, 61, 105, 1)' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/></svg>") !important;
  
}
.navbar-toggler{
  border-color: rgb(61, 61, 105) !important;
}
.navbar-custom {
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
  /* color: black !important; */
}
</style>