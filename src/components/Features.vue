<template>
  <section id="features">
    <div class="features--wrapper">
      <div class="features__title--wrapper">
        <div class="features__title--font">uniGO đem lại gì?</div>
        <div class="features__title--description">
          Giải pháp thông minh được phát triển trên nền tảng website và ứng dụng
          dành cho điện thoại di động với các tính năng
        </div>
      </div>
      <div class="features">
        <!-- chữ bên trái -->
        <div class="info_1" data-aos="fade-right" data-aos-duration="2000">
          <div class="info_1--title">
            <img src="../assets/number 1.svg" class="info_1--img" />
            <h3>Tìm kiếm thông tin địa điểm</h3>
          </div>
          <div style="margin-left: 2vw; color: #626262">
            Cho phép tìm kiếm và tra cứu thông tin các địa điểm trong nhà
            trường, xác định vị trí hiện tại bằng QR hoặc GPS...
          </div>
        </div>
        <div class="pic1-bg" data-aos="zoom-in-left" data-aos-duration="1500">
          <img class="pic1" src="../assets/qrcode-01 1.svg" />
        </div>
        <!-- ket thuc -->

        <!-- chữ bên phải -->
        <div class="pic2-bg" data-aos="zoom-in" data-aos-duration="2000">
          <img class="pic2" src="../assets/Pic.svg" />
        </div>
        <div class="info_2" data-aos="fade-left" data-aos-duration="2000">
          <div class="info_2--title">
            <img src="../assets/number 2.svg" class="info_2--img" />
            <h3>Tìm đường đi</h3>
          </div>
          <div style="margin-left: 2vw; color: #626262">
            Tính năng chỉ dẫn đường dễ dàng cho bạn chọn tuyến đường ngắn nhất
            đến địa điểm mà bạn muốn.
          </div>
        </div>
        <!-- ket thuc -->
        <div
          class="info_1"
          style="top: 59vw"
          data-aos="fade-right"
          data-aos-duration="1500"
        >
          <div class="info_1--title">
            <img src="../assets/number 3 1.svg" class="info_1--img" />
            <h3>Tra cứu thông tin phòng học</h3>
          </div>
          <div style="margin-left: 2vw; color: #626262">
            uniGO giúp bạn tra cứu thông tin phòng học, giảng viên và lớp học
            phần vào một thời điểm xác định.
          </div>
        </div>
        <div
          class="pic1-bg"
          style="top: 49vw; left: 57%"
          data-aos="zoom-in"
          data-aos-duration="2000"
        >
          <img class="pic1" src="../assets/3-01 1.svg" />
        </div>

        <div
          class="pic2-bg"
          style="top: 80vw"
          data-aos="zoom-in"
          data-aos-duration="1500"
        >
          <img class="pic2" src="../assets/tb-01 1.svg" />
        </div>
        <div
          class="info_2"
          style="top: 88vw"
          data-aos="fade-left"
          data-aos-duration="2000"
        >
          <div class="info_2--title">
            <img src="../assets/number 4.svg" class="info_2--img" />
            <h3>Thông báo sự kiện của trường</h3>
          </div>
          <div style="margin-left: 2vw; color: #626262">
            Kết nối đoàn trường và CLB đến gần sinh viên, Unigo thông báo thời
            gian địa điểm diễn ra, chia sẻ thông tin sự kiện đến các bạn có nhu
            cầu tham gia.
          </div>
        </div>
        <div id="users">
          <div></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Features",
};
</script>

<style>
.features {
  position: relative;
  padding: 10px;
  font-family: "Nunito Sans";
  width: auto;
  height: 100vw;
  background-image: url("../assets/line-01\ 1.svg");
  background-size: 100% 100%;
}

.line-bg {
  width: auto;
  height: 100%;
  position: absolute;
  top: 10vw;
  left: 50%;
  transform: translateX(-50%);
}

.line {
  width: auto;
  transform: rotate(0.8deg);
}

.pic1-bg {
  position: absolute;
  top: -8vw;
  left: 62%;
}

.pic1 {
  width: 25vw;
  height: 25vw;
}

.pic2-bg {
  position: absolute;
  top: 26vw;
  left: 20%;
}

.pic2 {
  width: 24vw;
  height: 24vw;
}

.info_1 {
  position: absolute;
  top: 0;
  left: 20%;
  font-size: 18px;
  width: 28vw;
}

.info_1--title {
  display: flex;
}

.info_1--img {
  width: 3vw;
  height: auto;
}

.info_2 {
  position: absolute;
  top: 33vw;
  right: 16%;
  font-size: 18px;
  width: 28vw;
}

.info_2--title {
  display: flex;
}

.info_2--img {
  width: 3vw;
  height: auto;
}

.features h3 {
  margin-left: 5px;
  color: #202d51;
}

.features--wrapper {
  padding: 12px;
}

.features__title--wrapper {
  width: 35vw;
  height: 15vw;
  margin-left: 12vw;
}

.features__title--font {
  font-size: 35px;
  font-weight: bold;
  color: #0b66bf;
}

.features__title--description {
  font-size: 18px;
  color: #626262;
}

</style>

