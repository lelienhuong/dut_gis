<template>
  <section id="footer">
    <div style="position: relative; height: 7vw">
      <a href="#features">
      <button id="footer--button" class="footer--button">
        <img class="footer--button-img" src="../assets/button play.svg" />
      </button>
      </a>
    </div>
    <div class="footer--wrap">
      <div class="footer__contact--wrapper">
        <img class="footer__logo" src="../assets/logo edit-01 1.svg" />
        <p class="footer__font-title">Thông tin liên hệ</p>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/Group (5).svg" />
          <p class="footer__font-content">unigo@gmail.com</p>
        </div>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/Vector.svg" />
          <p class="footer__font-content">facebook.com/unigo</p>
        </div>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/Vector (2).svg" />
          <p class="footer__font-content">
            (+84) 915 469 728 <br />
            (Phạm Mạnh Dũng - Quản lý dự án)
          </p>
        </div>
      </div>
      <div class="footer__link-sections">
        <p class="footer__font-title">Liên kết nhanh</p>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/fast-forward 1.svg" />
          <a class="footer__font-content" href="">Trang chủ</a>
        </div>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/fast-forward 1.svg" />
          <a class="footer__font-content" href="#features">Tính năng</a>
        </div>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/fast-forward 1.svg" />
          <a class="footer__font-content" href="#user">Đối tượng sử dụng</a>
        </div>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/fast-forward 1.svg" />
          <a class="footer__font-content" href="#questions"
            >Các câu hỏi thường gặp</a
          >
        </div>
        <div class="footer__contact-item--wrapper">
          <img class="footer__contact-item--icon" src="../assets/fast-forward 1.svg" />
          <a class="footer__font-content" href="#footer">Thông tin liên hệ</a>
        </div>
      </div>
      <div class="footer__form--wrapper">
        <p class="footer__font-title form-font">
          Bạn hãy để lại Gmail để nhận thông báo về ứng dụng sớm nhất nhé!
        </p>
        <div class="footer__form-subcribe--wrapper">
          <input placeholder="example@gmail.com" class="footer__form--input" />
          <button class="footer__form--button footer__font-content">
            Đăng kí
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style>
.footer--wrap {
  height: 18vw;
  width: auto;
  background-image: url("../assets/Rectangle\ 6.svg");
  background-size: cover;
  display: flex;
  color: white;
  padding: 1vw;
}

.footer__contact--wrapper {
  width: 30%;
  margin: auto;
}

.footer__logo {
  width: 10vw;
  height: auto;
}

.footer__font-title {
  font-weight: 800;
  font-size: 22px;
}

.footer__font-content {
  font-size: 16px;
  font-weight: 600;
  color: #fff;
}

.footer__contact-item--wrapper a {
  color: #ffffff;
  text-decoration: none;
}
.footer__contact-item--wrapper a:hover {
  text-decoration: underline;
}

.footer__contact-item--wrapper {
  display: flex;
  margin: 1vw 0 1vw 0;
}

.footer__contact-item--icon {
  width: 1vw;
  height: auto;
  margin-right: 7px;
}

.footer__link-sections {
  width: 25%;
  margin-top: 3vw;
}

.footer__form--wrapper {
  width: 36%;
  margin-top: 3vw;
}

.footer__form-subcribe--wrapper {
  display: flex;
  width: 23vw;
  height: 3vw;
  border-radius: 3vw;
  border-style: solid;
  border-color: #0a71c7;
  margin-top: 2vw;
}

.footer__form--input {
  width: 80%;
  color: #bdbdbd;
  font-weight: 600;
  font-size: 16px;
  background-color: transparent;
  border-top-left-radius: 3vw;
  border-bottom-left-radius: 3vw;
  margin-left: 1vw;
  border-color: transparent;
  outline: none;
}

::placeholder {
  color: #bdbdbd;
  font-weight: 600;
  font-size: 16px;
}

.footer__form--button {
  background-color: #0b66bf;
  border-radius: 3vw;
  width: 30%;
  border-color: transparent;
  outline: none;
  cursor: pointer;
}

.form-font {
  width: 30vw;
}
.footer--button {
  outline: none;
  border: transparent;
  background-color: transparent;
  position: absolute;
  right: 3vw;
  cursor: pointer;
}

.footer--button-img {
  width: 4vw;
  height: 4vw;
}
</style>