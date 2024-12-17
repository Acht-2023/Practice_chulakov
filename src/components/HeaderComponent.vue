<template>
    <header>
        <div class="headerline">
            <div>
                <img src="../assets/Logo.svg" alt="">
            </div>

            <div class="menu">
                <p>Главная</p>
                <p>Офисы</p>
                <p>Контакты</p>
                <p>О нас</p>
            </div>
        </div>

        <div class="right_block">
            <div class="info info_1" >
                <img src="../assets/img/mail.svg" alt="">
                <p>mail@coworking.ru</p>
            </div>

            <div class="info">
                <img src="../assets/img/call.svg" alt="">
                <p>+7 (999) 999-99-99</p>
            </div>

            <div class="info">
                <button class="but">Войти</button>
            </div>
        </div>
    </header>
</template>

<script>
    export default{}
</script>

<style>

header{
    display: flex; 
    justify-content: flex-end; 
    column-gap: 41px;
    height: 100px; 
    width: 100%;
}

.headerline{
    column-gap: 54px;
    display: flex;
    align-items: center;
}
.menu{
    display: flex;
    column-gap: 40px;
}
.menu p{
    font-size: 16px;
    font-weight: 600;
}

.right_block{
    display: flex;
    height: 100px;
    width: 750px;
    background-color: #2B7AF1;
    margin: 0;
    column-gap: 20px;
}

.info_1{
    margin-left: 59px;
}

.info{
    display: flex;
    column-gap: 10px;
    align-items: center;
}

.info img{
    width: 40px;
    height: 40px;
}

.info p{
    color: white;
    font-size: 16px;
    font-weight: 400;
}

.info button{
    width: 120px;
    height: 52px;
    margin-left: 13px;
}

</style>