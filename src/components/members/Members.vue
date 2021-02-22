<template>
  <section id="members" style="height: 800px">
    <div class="members--wrapper">
      <h1 class="section--title">
        Thành viên tham gia
        <!-- <img id="line" src="./assets/img/line_separator.svg" alt="" /> -->
        <div class="member__title-line--separator"></div>
      </h1>
      <MembersCarousel />
    </div>
  </section>
</template>

<script>
import MembersCarousel from "./components/members-carousel.vue";

export default {
  name: "Memebers",
  components: {
    MembersCarousel,
  },
};
</script>

<style>
@import url("../../assets/member/common.css");

#members {
  margin-left: 123px;
}
.member--wrapper {
  width: 100%;
}
.member__title-line--separator {
  margin-top: 8px;
  margin-left: 15px;
  width: 10vw;
  height: 4px;
  /* margin: auto; */
  background-image: linear-gradient(
    90deg,
    #4285f4 -19.99%,
    rgba(121, 220, 242, 0) 94.51%
  );
}

@media (max-width: 1399.98px) {

}
@media (max-width: 1199.98px) {
  #members {
    margin-left: 75px ;
  }
}
</style>