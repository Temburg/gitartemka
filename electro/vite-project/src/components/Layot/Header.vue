<template>
 <header class="header">
    <div class="header-top">
        <div class="img-left">
            <a href="#" class="header-logo"><img src="/svg/3.png" alt=""> Избранное</a>
            <a href="#" class="header-logo"><img src="/svg/7.png" alt=""> Обьекты</a>
            <a href="#" class="header-logo"><img src="/svg/6.png" alt=""> Устройства</a>
            <a href="#" class="header-logo"><img src="/svg/4.png" alt=""> Отчёты</a>
            <a href="#" class="header-logo"><img src="/svg/5.png" alt=""> События</a>
            <a href="#" class="header-logo"><img src="/svg/11.png" alt=""> Компания</a>
            <a href="#" class="header-logo"><img src="/svg/2.png" alt=""> Пользователь</a>
            <a href="#" class="header-logo"><img src="/svg/8.png" alt=""> Справочник</a>
        </div>
        <div class="right">
            <a href="#" class="header-logo"><img src="/svg/1.png" alt=""></a>
            <a href="#" class="header-logo"><img src="/svg/10.png" alt=""></a>
            <a href="#" class="header-logo"><img src="/svg/9.png" alt=""></a>
        </div>
    </div>
 </header>
</template>

<style lang="scss" scoped>
.header {
    &-top {
        display: flex;
        justify-content: space-between;
    }
    &-logo {
        color: #000;
        font-size: 18px;
        text-decoration: none;
        &:hover {
            text-decoration: underline;
        }
    }
}
.img-left {
	font-size: 14px;
	text-transform: uppercase;
}

.header-logo:after {
	content: "";
	display: block;
	width: 100%;
	height: 3px;
	background-color: #fce38a;
	opacity: 0;
	position: absolute;
	top: 100%;
	left: 0;
	z-index: 1;
	transition: opacity 0.2s linear;
}

.header-logo {
	display: inline-block;
	vertical-align: top;
	margin: 0 10px;
	position: relative;
	color: #000;
	text-decoration: none;
	transition: color 0.2s linear;
}

.header-logo:hover {
	color: #fce38a;
}



</style>