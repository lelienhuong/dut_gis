<template>
  <section id="members">
    <div class="members--wrapper">
      <!-- <h1 class="section--title">
        Thành viên tham gia
        <img id="line" src="./assets/img/line_separator.svg" alt="" />
      </h1> -->
      <div id="carousel" class="carousel slide" data-ride="carousel">
        <div class="position-relative" style="margin-top: 50px">
          <ol class="carousel-indicators">
            <li
              data-target="#carousel"
              data-slide-to="0"
              class="active department--name"
            >
              <div>
                <p>PM</p>
                <p>Project Manager</p>
              </div>
            </li>
            <li
              data-target="#carousel"
              data-slide-to="1"
              class="department--name"
            >
              <div>
                <p>BA</p>
                <p>Business Analyst</p>
              </div>
            </li>
            <li
              data-target="#carousel"
              data-slide-to="2"
              class="department--name"
            >
              <div>
                <p>UM</p>
                <p>UI/Map</p>
              </div>
            </li>
            <li
              data-target="#carousel"
              data-slide-to="3"
              class="department--name"
            >
              <div>
                <p>FE</p>
                <p>Front-End</p>
              </div>
            </li>
            <li
              data-target="#carousel"
              data-slide-to="4"
              class="department--name"
            >
              <div>
                <p>BA</p>
                <p>Back-End</p>
              </div>
            </li>
            <li
              data-target="#carousel"
              data-slide-to="5"
              class="department--name"
            >
              <div>
                <p>Mo</p>
                <p>Mobile</p>
              </div>
            </li>
          </ol>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="row">
              <div class="fl-cl">
                <img
                  src="../../src/assets/member/img/dung.svg"
                  alt="Mạnh Dũng"
                />
                <p class="member--name center-text" style="margin-top: 4px">
                  Phạm Mạnh Dũng
                </p>
              </div>
            </div>
          </div>

          <div class="carousel-item">
            <div class="row">
              <div class="fl-cl">
                <img
                  src="../../src/assets/member/img/linhhuong.svg"
                  alt="Linh Hương"
                />
                <p class="member--name center-text">Nguyễn Linh Hương</p>
              </div>

              <div class="fl-cl ml-55">
                <img
                  src="../../src/assets/member/img/mi.svg"
                  alt="Duyên Trần"
                />
                <div class="member--name" style="margin-top: 4px">
                  <p class="center-text">Trần Thị Thùy Duyên</p>
                  <p
                    class="department--name center-text"
                    style="margin-left: -14px"
                  >
                    BA-Lead
                  </p>
                </div>
              </div>

              <div class="fl-cl ml-55">
                <img
                  src="../../src/assets/member/img/nguyen.svg"
                  alt="Nguyên Trần"
                />
                <p class="member--name center-text" style="margin-top: -14px">
                  Trần Đình Phúc Nguyên
                </p>
              </div>
            </div>
          </div>

          <div class="carousel-item">
            <div class="row">
              <div class="fl-cl">
                <img
                  src="../../src/assets/member/img/oanh.svg"
                  alt="Kim Oanh"
                />
                <p class="member--name center-text" style="margin-top: 2px">
                  Đỗ Thị Kim Oanh
                </p>
              </div>

              <div class="fl-cl ml-55">
                <img src="../../src/assets/member/img/van.svg" alt="Tiến Văn" />
                <div class="member--name" style="margin-top: 4px">
                  <p class="center-text">Nguyễn Tiến Văn</p>
                  <p
                    class="department--name center-text"
                    style="margin-left: -15px"
                  >
                    Tech-Lead
                  </p>
                </div>
              </div>

              <div class="fl-cl ml-55">
                <img src="../../src/assets/member/img/hai.svg" alt="Hải Lê" />
                <p class="member--name center-text" style="margin-top: 2px">
                  Lê Hồng Hải
                </p>
              </div>
            </div>
          </div>

          <div class="carousel-item">
            <div class="row">
              <div class="fl-cl">
                <img
                  style="padding: 0px"
                  src="../../src/assets/member/img/trumcuoi.svg"
                  alt="Đức Huy"
                />
                <p class="member--name center-text" style="margin-top: 2px">
                  Nguyễn Hữu Đức Huy
                </p>
              </div>

              <div class="fl-cl ml-55">
                <img
                  src="../../src/assets/member/img/lienhuong.svg"
                  alt="Liên Hương"
                />
                <p class="member--name center-text" style="margin-top: 2px">
                  Lê Liên Hương
                </p>
              </div>
            </div>
          </div>

          <div class="carousel-item">
            <div class="row">
              <div class="fl-cl">
                <img
                  class="d-block"
                  src="../../src/assets/member/img/ichhoa.svg"
                  alt="Ích Hòa"
                />
                <p class="member--name center-text" style="margin-top: 2px">
                  Nguyễn ích Hòa
                </p>
              </div>
            </div>
          </div>

          <div class="carousel-item">
            <div class="row">
              <div class="fl-cl">
                <img
                  class="d-block"
                  src="../../src/assets/member/img/duc.svg"
                  alt="Nhân Đức"
                />
                <p class="member--name center-text" style="margin-top: 2px">
                  Lê Vĩnh Nhân Đức
                </p>
              </div>
            </div>
          </div>
        </div>
        <div id="carousel_control">
          <a
            class="carousel-control-prev"
            href="#carousel"
            role="button"
            data-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carousel"
            role="button"
            data-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
../../../assets/member/img/
<script>
// import Member from "./components/member.vue";
// import Navbtn from "../../src/assets/member/img"
export default {
  name: "App",
  // components: {
  // Member,
  // Navbtn,
  // },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* width: 1381.09px; */
}

.department--name {
  font-size: 20px !important;
  font-style: normal !important;
  font-weight: 600 !important;
  line-height: 27px !important;
  letter-spacing: 0em !important;
  color: #202d51;
}
.member--name {
  font-size: 25px;
  font-style: normal;
  font-weight: 700;
  line-height: 34px;
  letter-spacing: 0em;
  text-align: left;
  color: #202d51;
}

.row {
  justify-content: center;
  height: 322px;
}
.row img:not(:first-child) {
  padding-left: 100px;
}

.carousel-indicators li {
  text-indent: unset !important;
  width: auto;
  height: auto;
  background-color: unset !important ;
  cursor: pointer;
  margin-left: 70px !important;
  width: auto !important;
}

.carousel-indicators .active {
  background-color: unset;
  color: #0b66bf;
}
.carousel-indicators {
  justify-content: unset !important;
  bottom: 0 !important;
  left: 0px !important ;
  margin-left: 0px !important;
  margin-right: 5% !important;
  display: -webkit-box !important;
}
.carousel-inner {
  top: 100px;
  left: 12% !important;
  width: 75% !important;
}

.carousel-control-prev {
  position: absolute;
  top: 120px !important;
  width: 3% !important;
  left: 205px !important;
}
.carousel-control-next {
  position: absolute;
  top: 120px !important;
  width: 3% !important;
  right: 175px !important;
}

.carousel-control-next-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23000' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath d='M2.75 0l-1.5 1.5L3.75 4l-2.5 2.5L2.75 8l4-4-4-4z'/%3e%3c/svg%3e") !important;
}
.carousel-control-prev-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23000' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath d='M5.25 0l-4 4 4 4 1.5-1.5L4.25 4l2.5-2.5L5.25 0z'/%3e%3c/svg%3e") !important;
}

#members {
  margin-top: 100px;
  width: 100%;
  height: auto;
}
.members--wrapper {
  width: auto;
  height: auto;
}

.ml-55 {
  margin-left: 115px;
}
.fl-cl {
  display: flex;
  flex-direction: column;
}
.center-text {
  display: flex;
  justify-content: center;
}

/* @import url("../../src/assets/home/animation/Nav-underline.css");

.navbar {
  width: 100%;
}

.navbar-nav a {
  position: relative;
}
.navbar-nav li {
  margin-left: 14px;
}
.navbar-dark .navbar-nav .nav-link {
  text-decoration: none;
  font-weight: 600;
  font-size: 18px;
  color: #3e3e3e !important;
}

.navbar.navbar-dark.bg-dark {
  background-color: white !important;
  color: black;
}
.navbar-toggler-icon {
  background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'><path stroke='rgba(61, 61, 105, 1)' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/></svg>") !important;
}
.navbar-toggler {
  border-color: rgb(61, 61, 105) !important;
} */

/* .ml_450 {
  margin-left: 350px;
} */
/* 
.navbar--wrapper {
  width: 100%;
  background: #ffffff;
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
  z-index: 1300;
}
.navbar--logo {
  margin-left: 95px;
}

.navbar--custom {
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
}

@media (max-width: 1399.98px) {
  .navbar--logo {
    margin-left: 90px;
  }
  .ml_450 {
    margin-left: 160px;
  }
} */

/* Large devices (desktops, less than 1200px) */
/* @media (max-width: 1199.98px) {
  .navbar--logo {
    margin-left: 0px;
  }
  .ml_450 {
    display: flex;
    justify-content: flex-end;
    margin-left: 70px;
  }
  .navbar-nav li {
    margin-left: 0px;
  }
} */

/* Medium devices (tablets, less than 992px) */
/* @media (max-width: 991.98px) {
  .ml_450 {
    margin-left: 45px;
    justify-content: flex-start;
  }
} */

/* Small devices (landscape phones, less than 768px) */
/* @media (max-width: 767.98px) {
} */

/* X-Small devices (portrait phones, less than 576px) */
/* @media (max-width: 575.98px) {
} */

/* @media (max-width: 410.98px) {
} */

/* @media (max-width: 321px) {
} */
</style>
