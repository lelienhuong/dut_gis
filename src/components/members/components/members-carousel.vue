<template>
  <div class="members__carousel--wrapper">
    <b-carousel
      id="carousel-1"
      :interval="300000"
      controls
      indicators
      background="#ababab"
      style="text-shadow: 1px 1px 2px #333"
    >
      <b-carousel-slide>
        <template #img>
          <b-row>
            <b-col>
              <img
                class=""
                src="../../../assets/member/img/dung.svg"
                alt="Mạnh Dũng"
              />
              <p class="member__name">Phạm Mạnh Dũng</p>
            </b-col>
          </b-row>
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <b-row>
            <b-col>
              <img
                class=""
                src="../../../assets/member/img/linhhuong.svg"
                alt="Linh Hương"
              />
              <p class="member__name">Nguyễn Linh Hương</p>
            </b-col>

            <b-col>
              <img
                class=""
                src="../../../assets/member/img/mi.svg"
                alt="Thùy Duyên"
              />
              <p class="member__name">Trần Thị Thùy Duyên</p>
              <p
                class="member__name department--name"
                style="margin-top: -15px"
              >
                (Leader)
              </p>
            </b-col>

            <b-col>
              <img
                class=""
                src="../../../assets/member/img/nguyen.svg"
                alt="Phúc Nguyên"
              />
              <p class="member__name" style="margin-left: -35px">
                Trần Đình Phúc Nguyên
              </p>
            </b-col>
          </b-row>
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <b-row>
            <b-col>
              <img
                class=""
                src="../../../assets/member/img/oanh.svg"
                alt="Kim Oanh"
              />
              <p class="member__name">Đỗ Thị Kim Oanh</p>
            </b-col>

            <b-col>
              <img
                class=""
                src="../../../assets/member/img/van.svg"
                alt="Tiến Văn"
              />
              <p class="member__name">Nguyễn Tiến Văn</p>
              <p
                class="member__name department--name"
                style="margin-top: -15px"
              >
                Tech-Lead
              </p>
            </b-col>

            <b-col>
              <img
                class=""
                src="../../../assets/member/img/hai.svg"
                alt="Hồng Hải"
              />
              <p class="member__name">Lê Hồng Hải</p>
            </b-col>
          </b-row>
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <b-row>
            <b-col>
              <img
                class=""
                src="../../../assets/member/img/lienhuong.svg"
                alt="Liên Hương"
              />
              <p class="member__name">Lê Liên Hương</p>
            </b-col>

            <b-col>
              <img
                class=""
                src="../../../assets/member/img/trumcuoi.svg"
                alt="Đức Huy"
              />
              <p class="member__name">Nguyễn Hữu Đức Huy</p>
              <p class="member__name department--name">a.k.a Trùm-Cuối</p>
            </b-col>
          </b-row>
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <b-row>
            <b-col>
              <img
                class=""
                src="../../../assets/member/img/ichhoa.svg"
                alt="Ích Hòa"
              />
              <p class="member__name">Nguyễn Ích Hòa</p>
            </b-col>
          </b-row>
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <b-row>
            <b-col>
              <img
                class=""
                src="../../../assets/member/img/duc.svg"
                alt="Nhân Đức"
              />
              <p class="member__name">Lê Vĩnh Nhân Đức</p>
            </b-col>
          </b-row>
        </template>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  name: "MembersCarousel",
};
</script>

<style>
.carousel-item {
  height: 306px;
}
.row {
  height: 100%;
  justify-content: space-around;
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

@media (max-width: 1399.98px) {
  .members__carousel--wrapper {
    width: 94%;
    /* display: flex;
    justify-content: center; */
  }
  .carousel-control-prev {
    width: 2% !important;
  }
  .carousel-control-next {
    width: 2% !important;
  }
}
</style>