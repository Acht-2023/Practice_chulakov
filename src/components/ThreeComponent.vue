<template>
  <div class="contact">
    <div>
      <h1>Контакты</h1>
      <div class="contact_info">
        <img src="../assets/img/Phone.svg" alt="" />
        <p>Ростовская обл., г. Ростов-на-Дону</p>
      </div>
      <div class="contact_info">
        <img src="../assets/img/Mail_two.svg" alt="" />
        <p>mail@coworking.ru</p>
      </div>
      <div class="contact_info">
        <img src="../assets/img/Phone_Icon.svg" alt="" />
        <p>+7 (999) 999-99-99</p>
      </div>

      <div class="social social_top">
        <div class="social_info">
          <img src="../assets/img/instagramm.svg" alt="" />
          <p>coworking</p>
        </div>
        <div>
          <button class="but but_four">Подписаться</button>
        </div>
      </div>
      <div class="social">
        <div class="social_info">
          <img src="../assets/img/vk.svg" alt="" />
          <p>coworking</p>
        </div>
        <div>
          <button class="but but_four">Подписаться</button>
        </div>
      </div>
    </div>

    <div style="position: relative; overflow: hidden; margin-right: 80px">
      <a
        href="https://yandex.ru/maps/39/rostov-na-donu/search/%D0%9A%D0%BE%D0%B2%D0%BE%D1%80%D0%BA%D0%B8%D0%BD%D0%B3/?utm_medium=mapframe&utm_source=maps"
        style="color: #eee; font-size: 12px; position: absolute; top: 0px"
        >Коворкинг в Ростове‑на‑Дону</a
      ><a
        href="https://yandex.ru/maps/39/rostov-na-donu/?utm_medium=mapframe&utm_source=maps"
        style="color: #eee; font-size: 12px; position: absolute; top: 14px"
        >Ростов‑на‑Дону</a
      ><iframe
        src="https://yandex.ru/map-widget/v1/?display-text=%D0%9A%D0%BE%D0%B2%D0%BE%D1%80%D0%BA%D0%B8%D0%BD%D0%B3&ll=39.701883%2C47.237973&mode=search&sll=39.701883%2C47.237952&text=category_id%3A%2860934766081%29&z=13"
        width="768"
        height="430"
        frameborder="1"
        allowfullscreen="true"
        style="position: relative"
      ></iframe>
    </div>
  </div>
</template>
<script></script>

<style>
.contact {
  margin-top: 113px;
  margin-left: 80px;
  display: flex;
  column-gap: 139px;
}

.contact h1 {
  color: #2b7af1;
  font-size: 36px;
  margin-bottom: 27px;
}

.contact_info {
  display: flex;
  align-items: center;
  column-gap: 20px;
  margin-top: 15px;
}

.contact_info p {
  font-size: 18px;
}

.social {
  display: flex;
  align-items: center;
  column-gap: 169px;
  margin-top: 15px;
}

.social_info {
  display: flex;
  align-items: center;
  column-gap: 20px;
}

.social_info p {
  font-size: 18px;
}

.but_four {
  width: 157px;
  height: 33px;
  font-size: 14px;
}

.social_top {
  margin-top: 90px;
}

.map {
  width: 758px;
  height: 430px;
}
</style>
