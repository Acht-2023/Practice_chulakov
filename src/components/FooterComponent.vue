<template>
  <footer class="footer">
    <div class="">
      <div class="footer__info">
        <div class="footer__info_set">
          <img src="../assets/Logo.svg" alt="" />
          <div class="menu menu_two">
            <p>Главная</p>
            <p>Коворкинг</p>
            <p>Контакты</p>
            <p>О нас</p>
          </div>
          <div class="mail_info">
            <img src="../assets/img/Mail_two.svg" alt="" />
            <p>mail@coworking.ru</p>
          </div>
          <div class="mail_info">
            <img src="../assets/img/Phone_Icon.svg" alt="" />
            <p>+7 (999) 999-99-99</p>
          </div>
          <div style="column-gap: 10px; display: flex">
            <img src="../assets/img/telegramm.svg" alt="" />
            <img src="../assets/img/facebook.svg" alt="" />
            <img src="../assets/img/vk.svg" alt="" />
            <img src="../assets/img/instagramm.svg" alt="" />
          </div>
        </div>
      </div>
      <div class="copyright darkened">
        <div class="copyright__set">
          <p>© Copyright 2024, «Коворкинг»</p>
          <p>Пользовательское соглашение</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script></script>

<style>
.footer {
  width: 100%;
  height: 557px;
  background-image: url(../assets/img/foot.jpg);
  margin-top: -198px;
  display: flex;
  align-items: flex-end;
}

.footer__info {
  margin-left: 80px;
  width: 1280px;
  border-bottom: 1px solid #ffffff;
}

.menu_two p {
  color: white;
}

.mail_info {
  display: flex;
  column-gap: 20px;
  align-items: center;
}

.mail_info p {
  color: white;
  font-size: 16px;
}

.copyright {
  background-color: white;
  transition:
    background-color 0.3s,
    color 0.3s;
  width: 1440px;
  height: 60px;
}

.footer__info_set {
  display: flex;
  column-gap: 40px;
  align-items: center;
  margin-bottom: 20px;
}

.darkened {
  background-color: rgba(0, 0, 0, 0.7);
  color: white;
}
.copyright p {
  color: white;
  font-size: 14px;
}

.copyright__set {
  gap: 229px;
  display: flex;
  align-items: center;
  width: 679px;
  height: 60px;
  margin-left: 155px;
}
</style>
