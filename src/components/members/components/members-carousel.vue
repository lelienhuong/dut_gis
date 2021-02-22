<template>
  <div class="members__carousel--wrapper">
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
          <b-row>
            <b-col>
              <img src="../../../assets/member/img/dung.svg" alt="Mạnh Dũng" />
              <p class="member--name center-text" style="margin-top: 4px">
                Phạm Mạnh Dũng
              </p>
            </b-col>
          </b-row>
        </div>

        <div class="carousel-item">
          <b-row>
            <b-col>
              <img
                src="../../../assets/member/img/linhhuong.svg"
                alt="Linh Hương"
              />
              <p class="member--name center-text">Nguyễn Linh Hương</p>
            </b-col>

            <b-col class="ml-55">
              <img src="../../../assets/member/img/mi.svg" alt="Duyên Trần" />
              <div class="member--name">
                <p class="center-text center-text">Trần Thị Thùy Duyên</p>
                <p
                  class="department--name center-text"
                  style="margin-top: -10px"
                >
                  BA-Lead
                </p>
              </div>
            </b-col>

            <b-col class="ml-55">
              <img
                src="../../../assets/member/img/nguyen.svg"
                alt="Nguyên Trần"
              />
              <p class="member--name center-text" style="margin-left: -20px">
                Trần Đình Phúc Nguyên
              </p>
            </b-col>
          </b-row>
        </div>

        <div class="carousel-item">
          <b-row>
            <b-col>
              <img src="../../../assets/member/img/oanh.svg" alt="Kim Oanh" />
              <p class="member--name center-text" style="margin-top: 2px">
                Đỗ Thị Kim Oanh
              </p>
            </b-col>

            <b-col class="ml-55">
              <img src="../../../assets/member/img/van.svg" alt="Tiến Văn" />
              <div class="member--name" style="margin-top: 4px">
                <p class="center-text center-text">Nguyễn Tiến Văn</p>
                <p
                  class="department--name center-text"
                  style="margin-top: -10px"
                >
                  Tech-Lead
                </p>
              </div>
            </b-col>

            <b-col class="ml-55">
              <img src="../../../assets/member/img/hai.svg" alt="Hải Lê" />
              <p class="member--name center-text" style="margin-top: 2px">
                Lê Hồng Hải
              </p>
            </b-col>
          </b-row>
        </div>

        <div class="carousel-item">
          <b-row style="justify-content: center">
            <b-col>
              <img
                style="padding: 0px"
                src="../../../assets/member/img/trumcuoi.svg"
                alt="Đức Huy"
              />
              <p class="member--name center-text" style="margin-top: 2px">
                Nguyễn Hữu Đức Huy
              </p>
              <p class="department--name center-text" style="margin-top: -10px">
                a.k.a Trùm-Cuối
              </p>
            </b-col>

            <b-col class="ml-55">
              <img
                src="../../../assets/member/img/lienhuong.svg"
                alt="Liên Hương"
              />
              <p class="member--name center-text" style="margin-top: 2px">
                Lê Liên Hương
              </p>
            </b-col>
          </b-row>
        </div>

        <div class="carousel-item">
          <b-row>
            <b-col>
              <img
                class="d-block"
                src="../../../assets/member/img/ichhoa.svg"
                alt="Ích Hòa"
              />
              <p class="member--name center-text" style="margin-top: 2px">
                Nguyễn ích Hòa
              </p>
            </b-col>
          </b-row>
        </div>

        <div class="carousel-item">
          <b-row>
            <b-col>
              <img
                class="d-block"
                src="../../../assets/member/img/duc.svg"
                alt="Nhân Đức"
              />
              <p class="member--name center-text" style="margin-top: 2px">
                Lê Vĩnh Nhân Đức
              </p>
            </b-col>
          </b-row>
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
</template>

<script>
export default {
  name: "MembersCarousel",
};
</script>


<style>
.ml-55 {
  margin-left: 100px;
}
.carousel-item {
  height: 315px;
}
.row {
  /* height: 100%; */
  justify-content: center;
  margin-left: -70px !important;
}
.col {
  flex-grow: unset !important;
}
.carousel-control-next-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23000' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath d='M2.75 0l-1.5 1.5L3.75 4l-2.5 2.5L2.75 8l4-4-4-4z'/%3e%3c/svg%3e") !important;
}
.carousel-control-prev-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23000' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath d='M5.25 0l-4 4 4 4 1.5-1.5L4.25 4l2.5-2.5L5.25 0z'/%3e%3c/svg%3e") !important;
}

.carousel-indicators li {
  text-indent: unset !important;
  width: auto;
  height: auto;
  background-color: unset !important ;
  cursor: pointer;
  margin-left: 70px !important;
  width: auto !important;
  opacity: 1 !important;
}
.carousel-indicators {
  justify-content: unset !important;
  bottom: 0 !important;
  left: 0px !important ;
  margin-left: 0px !important;
  /* margin-right: 5% !important; */
  display: -webkit-box !important;
}

.carousel-indicators .active {
  background-color: unset;
  color: #0b66bf;
}
.carousel-inner {
  top: 100px;
  left: 10% !important;
  width: 75% !important;
}

.carousel-control-prev {
  position: absolute;
  top: 120px !important;
  width: 3% !important;
  /* left: 205px !important; */
}
.carousel-control-next {
  position: absolute;
  top: 120px !important;
  width: 3% !important;
  right: 115px !important;
}

.carousel-control-next-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23000' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath d='M2.75 0l-1.5 1.5L3.75 4l-2.5 2.5L2.75 8l4-4-4-4z'/%3e%3c/svg%3e") !important;
}
.carousel-control-prev-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23000' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath d='M5.25 0l-4 4 4 4 1.5-1.5L4.25 4l2.5-2.5L5.25 0z'/%3e%3c/svg%3e") !important;
}

@media (max-width: 1399.98px) {
  .ml-55 {
    margin-left: 30px !important;
  }
  .members__carousel--wrapper {
    width: 94%;
    /* display: flex;
      justify-content: center; */
  }
  .carousel-inner {
    left: 3% !important;
    width: 94% !important;
  }
  .carousel-indicators li {
    margin-left: 50px !important;
  }
  .carousel-control-prev {
    width: 2% !important;
  }
  .carousel-control-next {
    width: 2% !important;
    right: 60px !important;
  }
}

/* Large devices (desktops, less than 1200px) */
@media (max-width: 1199.98px) {
  .carousel-inner {
    width: 100% !important;
    left: 0% !important;
  }
  .carousel-indicators {
    left: 0% !important;
  }
  .carousel-indicators li {
    margin-left: 40px !important;
  }
  .ml-55 {
    margin-left: 25px !important;
  }
  .carousel-control-prev {
    left: 40px !important;
  }
  .carousel-control-next {
    right: 40px !important;
  }
}

/* Medium devices (tablets, less than 992px) */
@media (max-width: 991.98px) {
  .row {
    height: 879px;
  }
  #carousel_control {
    display: none !important  ;
  }
  .memberPhoto__768 {
    flex-direction: column !important ;
  }
  .carousel-indicators li:not(:first-child) {
    margin-left: 25px !important;
  }
  .carousel-indicators li:first-child {
    margin-left: 10px !important;
  }
  .memberPhoto__768 img {
    padding-left: 0 !important;
    margin-left: 20px !important;
  }
  .memberPhoto__768 .ml-55 {
    margin-left: 0;
  }
  .memberPhoto__768 img:first-child {
    margin-left: 0px !important;
  }
}
</style>