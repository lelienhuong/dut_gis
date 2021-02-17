<template>
  <section id="questions">
    <div class="question--wrapper">
      <div class="question__title--wrapper">
        <div class="question__title-line--left"></div>
        <div class="question__title--font">Câu hỏi thường gặp</div>
        <div class="question__title-line--right"></div>
      </div>
      <div class="question__content--wrapper">
        <div class="question__item--wrapper">
          <div :class="isAnswer0 ? wrapper2 : wrapper">
            <div class="question__detail">
              <p :class="isAnswer0 ? font2 : font">DSC - DUT là gì?</p>
              <button
                :class="isAnswer0 ? button2 : button"
                @click="changeStatus0"
              >
                <img
                  :class="isAnswer0 ? icon2 : icon"
                  src="../assets/plus.svg"
                />
              </button>
            </div>
          </div>
          <div v-if="isAnswer0" class="question__answer--wrapper">
            <div class="question__answer--detail">
              <b
                >DSC - DUT (Developer Student Clubs - Da Nang University of
                Science and Technology)</b
              >
              là cộng đồng do Google Developers bảo trợ. Gồm các bạn sinh viên
              trẻ năng động đến từ các trường đại học trực thuộc đại học Đà
              Nẵng, quan tâm tới việc xây dựng và đưa ra các giải pháp phát
              triển cộng đồng.
            </div>
          </div>
        </div>
        <div class="question__item--wrapper">
          <div :class="isAnswer1 ? wrapper2 : wrapper">
            <div class="question__detail">
              <p :class="isAnswer1 ? font2 : font">
                Sản phẩm có mất phí sử dụng không?
              </p>
              <button
                :class="isAnswer1 ? button2 : button"
                @click="isAnswer1 = !isAnswer1"
              >
                <img
                  :class="isAnswer1 ? icon2 : icon"
                  src="../assets/plus.svg"
                />
              </button>
            </div>
          </div>
          <div v-if="isAnswer1" class="question__answer--wrapper">
            <div class="question__answer--detail">
              <b>Hoàn toàn không.</b> Đây là sản phẩm phi lợi nhuận được phát
              triển bởi DSC - DUT cho đơn vị trường Đại học Bách Khoa, hỗ trợ
              tra cứu thông tin địa điểm nhanh chóng và chính xác.
            </div>
          </div>
        </div>
        <div class="question__item--wrapper">
          <div :class="isAnswer2 ? wrapper2 : wrapper">
            <div class="question__detail">
              <p :class="isAnswer2 ? font2 : font">
                Ứng dụng có cần sử dụng Internet không?
              </p>
              <button
                :class="isAnswer2 ? button2 : button"
                @click="isAnswer2 = !isAnswer2"
              >
                <img
                  :class="isAnswer2 ? icon2 : icon"
                  src="../assets/plus.svg"
                />
              </button>
            </div>
          </div>
          <div v-if="isAnswer2" class="question__answer--wrapper">
            <div class="question__answer--detail">
              Hiện tại, sản phẩm sẽ được thiết kế dùng trước trên website và mở
              rộng ra điện thoại. Trước mắt, các thiết bị sẽ yêu cầu
              <b>có kết nối internet</b> (3G/4G/Wifi) để có thể sử dụng.
            </div>
          </div>
        </div>
        <div class="question__item--wrapper">
          <div :class="isAnswer3 ? wrapper2 : wrapper">
            <div class="question__detail">
              <p :class="isAnswer3 ? font2 : font">
                Mục đích ra đời của uniGO là gì?
              </p>
              <button
                :class="isAnswer3 ? button2 : button"
                @click="isAnswer3 = !isAnswer3"
              >
                <img
                  :class="isAnswer3 ? icon2 : icon"
                  src="../assets/plus.svg"
                />
              </button>
            </div>
          </div>
          <div v-if="isAnswer3" class="question__answer--wrapper">
            <div class="question__answer--detail">
              <b>uniGO</b> ra đời với mong muốn xây dựng và đóng góp vào cộng
              đồng. Được mọi người đón nhận và từng bước ứng dụng trong thực
              tiễn.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Questions",
  data() {
    return {
      isAnswer0: false,
      isAnswer1: false,
      isAnswer2: false,
      isAnswer3: false,
      button: "question__content--button",
      button2: "question__content--button2",
      font: "question__detail--font",
      font2: "question__detail--font2",
      icon: "question__content--button-icon",
      icon2: "question__content--button-icon2",
      wrapper: "question__detail--wrapper",
      wrapper2: "question__detail--wrapper2",
    };
  },
  methods: {
    changeStatus0() {
      this.isAnswer0 = !this.isAnswer0;
      this.className = "question__content--button2";
    },
  },
};
</script>

<style>
* {
  font-family: "Nunito Sans";
}
.question__detail--wrapper2 {
  width: 100%;
  height: 3vw;
  border-style: solid;
  border-width: thin;
  background-image: linear-gradient(to right, #fc4c3f, #ff796a);
  border-radius: 3vw;
  position: relative;
  border-color: #cecccc;
}

.question__content--button2 {
  width: 2vw;
  height: 2vw;
  margin: auto;
  border-radius: 50%;
  outline: none;
  background-color: #ffffff;
  border-color: transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}

.question__detail--font2 {
  width: 85%;
  font-size: 19px;
  font-family: "Nunito Sans";
  /* color: #fff; */
  margin-left: 3vw;
  margin: auto;
  margin-left: 1vw;
  font-weight: 600;
  color: #ffffff;
}

.question__content--button-icon2 {
  width: 1vw;
  height: auto;
  filter: invert(40%) sepia(50%) saturate(4780%) hue-rotate(340deg)
    brightness(110%) contrast(98%);
  transform: rotate(45deg);
}

.question--wrapper {
  margin: auto;
  height: 50vw;
}

.question__title--wrapper {
  display: flex;
  height: 3vw;
  width: 33vw;
  margin: auto;
}

.question__title-line--left {
  width: 5vw;
  margin: auto;
  height: 3px;
  background-image: linear-gradient(to right, #fff, #79dcf2, #4285f4);
}

.question__title-line--right {
  width: 5vw;
  margin: auto;
  height: 3px;
  background-image: linear-gradient(to right, #4285f4, #79dcf2, #fff);
}

.question__title--font {
  color: #0b66bf;
  font-size: 35px;
  font-weight: bold;
  margin: auto;
}

.question__content--wrapper {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  height: auto;
}

.question__item--wrapper {
  width: 30%;
  padding: 3vw;
  margin: 0vw 6vw 0vw 6vw;
}

.question__detail--wrapper {
  width: 100%;
  height: 3vw;
  border-style: solid;
  border-width: thin;
  /* background-image: linear-gradient(to right, #FC4C3F, #FF796A); */
  border-radius: 3vw;
  position: relative;
  border-color: #cecccc;
}

.question__detail--wrapper:hover {
  box-shadow: 3px 3px 6px #79a8f3;
}

.question__detail {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  display: flex;
  margin: auto;
  width: 100%;
}

.question__detail--font {
  width: 85%;
  font-size: 19px;
  font-family: "Nunito Sans";
  /* color: #fff; */
  margin-left: 3vw;
  color: #202d51;
  margin: auto;
  margin-left: 1vw;
  font-weight: 600;
}

.question__content--button {
  width: 2vw;
  height: 2vw;
  margin: auto;
  border-radius: 50%;
  outline: none;
  background-image: linear-gradient(to right, #fc4c3f, #ff796a);
  border-color: transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}

.question__content--button-icon {
  width: 1vw;
  height: auto;
  filter: invert(1);
  /* transform: rotate(45deg); */
}

.question__answer--wrapper {
  display: flex;
  width: 100%;
}

.question__answer--detail {
  width: 100%;
  color: #626262;
  margin-top: 1vw;
  border-left-style: solid;
  border-width: thin;
  border-left-color: #cecccc;
  padding: 3px;
  margin-left: 10px;
}

</style>
