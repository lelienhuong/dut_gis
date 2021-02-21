<template>
  <div class="members__carousel--wrapper">
    <b-carousel
      id="carousel-1"
      :interval="4000"
      controls
      indicators
      background="#ababab"

      style="text-shadow: 1px 1px 2px #333"
    >
      <b-carousel-slide>
        <template #img>
          <img
            class=""
            src="../../../assets/member/img/dung.svg"
            alt="Mạnh Dũng"
          />
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <img
            class=""
            src="../../../assets/member/img/linhhuong.svg"
            alt="Linh Hương"
          />
          <img
            class=""
            src="../../../assets/member/img/mi.svg"
            alt="Thùy Duyên"
          />
          <img
            class=""
            src="../../../assets/member/img/nguyen.svg"
            alt="Phúc Nguyên"
          />
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <img
            class=""
            src="../../../assets/member/img/oanh.svg"
            alt="Kim Oanh"
          />
          <img
            class=""
            src="../../../assets/member/img/van.svg"
            alt="Tiến Văn"
          />
          <img
            class=""
            src="../../../assets/member/img/hai.svg"
            alt="Hồng Hải"
          />
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <img
            class=""
            src="../../../assets/member/img/lienhuong.svg"
            alt="Liên Hương"
          />
          <img
            class=""
            src="../../../assets/member/img/trumcuoi.svg"
            alt="Đức Huy"
          />
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <img
            class=""
            src="../../../assets/member/img/ichhoa.svg"
            alt="Ích Hòa"
          />
        </template>
      </b-carousel-slide>

      <b-carousel-slide>
        <template #img>
          <img
            class=""
            src="../../../assets/member/img/duc.svg"
            alt="Nhân Đức"
          />
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
</style>