<template>
  <div class="navbar--wrapper">
    <b-navbar toggleable="lg" style="width:100%;">
      <b-navbar-brand href="#" class="navbar--logo">
        <img src="../../../assets/logo-text.svg" alt="logo-text" />
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse" ></b-navbar-toggle>

      <b-collapse class="ml_360" id="nav-collapse" is-nav>
        <b-navbar-nav class="navbar--underline navbar--text">
          <b-nav-item href="#" class="my-auto"> Trang chủ </b-nav-item>
          <b-nav-item href="#" class="my-auto">Tính năng</b-nav-item>
          <b-nav-item href="#" class="my-auto">Đối tượng sử dụng</b-nav-item>
          <b-nav-item href="#" class="my-auto">Q&A</b-nav-item>
          <b-nav-item href="#" class="my-auto">Thông tin liên hệ</b-nav-item>
          <b-nav-item href="#" class="my-auto">
            <Navbtn />
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
import Navbtn from "./Nav-btn.vue";
export default {
  name: "Navbar",
  components: {
    Navbtn,
  },
};
</script>

<style>
@import url("../../../assets/home/animation/Nav-underline.css");


.navbar-nav a {
  position: relative;
}
.navbar-nav li{
  margin-left: 14px;
}
.nav-item {
  display: flex;
  /* align-items: center !important; */
}
.ml_360{
  margin-left: 228px;
}

.navbar--wrapper {
  width: 100%;
  height: 70px;
  background: #ffffff;
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
  z-index: 1300;
  display: flex;
  align-items: center;
  position: absolute;
}
.navbar--logo {
  margin-left: 107px;
}
.navbar--text {
  text-decoration: none;
  font-weight: 600;
  font-size: 18px;
  color: #3e3e3e !important;
}
</style>