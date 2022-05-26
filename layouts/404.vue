<template>
    <div class="wrap-404">
        <div class="logo">
            <a href="https://piepme.com/">
                <img src="@/assets/images/landing/logo-with-txt.svg">
            </a>
        </div>

        <div class="content">
            <h1>404</h1>
            <p>Xin lỗi bạn,</p>
            <p>hệ thống không tìm thấy trang này</p>
            <div class="sub">
                <p><a href="https://piepme.com/">Quay lại</a></p>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
.wrap-404{margin:0 auto;width:1000px;}
.wrap-404 .logo{width: 100%;    text-align: center;    padding: 150px 0 50px;}
.wrap-404 .content{margin-top: 50px;}
.wrap-404 .content h1{font-family: 'Boogaloo', cursive;font-size: 216px;line-height: 216px;color: rgb(216,216,216);text-align: center;margin-bottom:1px;margin-top: 0}
.wrap-404 .content p{font-family: 'Open Sans';font-weight: normal;color: #4d4d4d;font-size: 20px;margin: 0px;text-align: center;}
.wrap-404 .content p span{color: lightgreen;}
.wrap-404 .sub {margin-top: 50px;}
.wrap-404 .sub a{color: white;background-image: linear-gradient(to right, #ff7a96, #f1974a);text-decoration: none;padding:10px 40px;font-size: 24px;   font-family: arial, serif;font-weight: normal;border-radius: 50px;cursor: pointer;}
.wrap-404 .footer{color: #8F8E8C;position: absolute;right:10px;bottom:10px;}
.wrap-404 .footer a{color:rgb(228, 146, 162);}
</style>
