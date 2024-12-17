<template>
    <div class="mainy">
        <div>
            <div class="text">
                <h1>
                    Платформа для поиска коворкинга
                </h1>
            </div>
            <div class="text_2">
                <p>
                    На длительный срок
                    или посуточно
                </p>
            </div>
            <div>
                <button class="but but_two">
                    Смотреть варианты
                </button>
            </div>
        </div>
        <div class="blue_block">
            <img src="../assets/img/photo.png" alt="">
        </div>
    </div>

    <div class="block_info">
        <div class="block_info_text">
            <img src="../assets/img/deal.svg" alt="">
            <p>Заключаем договоры, предоставляет отчётные документы</p>
        </div>
        <div class="block_info_text">
            <img src="../assets/img/money.svg" alt="">
            <p>Наличный и безналичный расчёт</p>
        </div>
        <div class="block_info_text">
            <img src="../assets/img/time.svg" alt="">
            <p>Бронирование круглосуточно</p>
        </div>
        <div class="block_info_text">
            <img src="../assets/img/guard.svg" alt="">
            <p>Полная конфиденциальность</p>
        </div>
    </div>



</template>
<script>
    export default{}
</script>

<style>
.mainy{
    display: flex;
    justify-content: flex-end;
    column-gap: 172px;
}

.blue_block{
    width: 750px;
    height: 710px;
    background-color: #2B7AF1;
}

.blue_block img{
    margin: 39px -145px;
}

.but_two{
    margin-top: 60px;
    width: 251px;
    height: 52px;
}

.text{
    width: 438px;
}

.text h1{
    font-size: 40px;
    margin-top: 113px;
}

.text_2{
    width: 265px;
    font-family: Arial, sans-serif;
}

.text_2 p{
    margin-top: 44px;
    font-size: 24px;
}

.block_info{
    display: flex;
    column-gap: 20px;
    justify-content: center;
    margin: -130px 0 0;
}

.block_info_text{
    width: 305px;
      height: 231px;
      background-color: #fff; /* Белый фон */
      border-radius: 10px; /* Скруглённые углы */
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4); /* Тень */
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      font-family: Arial, sans-serif;
}

.block_info_text img{
    margin-top: 40px;
}

.block_info_text p{
    font-size: 16px;
    width: 195px;
    font-weight: 400px;
    margin-top: 26px;
}

</style>