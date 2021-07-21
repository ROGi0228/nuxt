<template>
    <div class="header">

        <div class="background">
        </div>

        <div class="header__box">
            <img src="../static/assets/images/ЯЧ.png" alt="" class="logo">
            <select name="language" id="language">

                <option value="1">Русский</option>
                <option value="2">English</option>
                <option value="3">Ukraine</option>

            </select>
        </div>


        <main class="main">
            <div class="container">
                <div class="main__box">
                    <div class="main__header">
                        <h1 class="main__title">
                            МОНЕТЕЗИРУЙ СВОЙ СКИЛЛ...
                        </h1>
                        <p class="main__suntitle">
                            Играй в любимые онлайн-игры и фарми реальный кэш на собственных победах
                        </p>

                        <div class="main__buttons">
                            <button class="login">Вход</button>
                            <button class="reg">Регистрация</button>
                        </div>
                    </div>

                    <div class="main__about-us">
                        <div class="about-us1">
                            <p class="about-us__title">СМУРФЫ НЕ ПРОЙДУТ!</p>
                            <img src="../static/assets/images/about-us/1.png" alt="" class="about-us__img">
                        </div>
                            
                        <div class="about-us2">
                            <p class="about-us__title">БЕЗ РУИНЕРОВ И ЛИВЕРОВ</p>
                            <img src="../static/assets/images/about-us/2.png" alt="" class="about-us__img">
                        </div>

                        <div class="about-us3">
                            <p class="about-us__title">ЧИТ - КОНТРОЛЬ</p>
                            <img src="../static/assets/images/about-us/3.png" alt="" class="about-us__img">
                        </div>

                        <div class="about-us4">
                            <p class="about-us__title">ТОТАЛЬНЫЙ БАН</p>
                            <img src="../static/assets/images/about-us/4.png" alt="" class="about-us__img">
                        </div>

                        <div class="about-us5">
                            <p class="about-us__title">КАЛИБРОВКА АККАУНТА</p>
                            <img src="../static/assets/images/about-us/5.png" alt="" class="about-us__img">
                        </div>
                    </div>
                </div>
            </div>
        </main>
        
        
    </div>
    
</template>

<style scoped>
    *{
        box-sizing: border-box;
    }



    .main__about-us{
        padding-top: 87px;
        display: flex;
        justify-content: space-between;
        text-align: center;
    }

    .background{
        background: url("../static/assets/images/dota-2-background 1.png") right bottom no-repeat;
        position: absolute;
        width: 1130px;
        height: 1211px;
        top: 0;
    }


    .login, .reg{
        outline: none;
        border: none;
        background: linear-gradient(91.72deg, rgba(97, 0, 255, 0.14) -8.47%, rgba(0, 0, 0, 0) 127.28%), radial-gradient(56.12% 246.25% at 29.62% -98.75%, #CC00FF 0%, rgba(0, 0, 0, 0) 100%, rgba(0, 41, 255, 0) 100%), linear-gradient(261.57deg, #8000FF -2.36%, rgba(0, 169, 169, 0.67) 71.78%);
        border-radius: 12px;
        height: 39px;
        margin: 0 auto;
        color: #fff;
        font-weight: bold;
    }

    .login{
        padding-left: 22px;
        padding-right: 22px;
        margin-right: 5px;  
    }
    .reg{
        padding-left: 54px;
        padding-right: 54px;
    }


    .container{
        width: 100%;
        max-width: 1214px;
        margin: 0 auto;
    }


    .header__box{
        display: flex;
        justify-content: space-between;
        color: #fff;
        z-index: 1;
    }
    
    #language{
        position: absolute;
        background: linear-gradient(91.72deg, rgba(97, 0, 255, 0.14) -8.47%, rgba(0, 0, 0, 0) 127.28%), radial-gradient(56.12% 246.25% at 29.62% -98.75%, #CC00FF 0%, rgba(0, 0, 0, 0) 100%, rgba(0, 41, 255, 0) 100%), linear-gradient(261.57deg, #8000FF -2.36%, rgba(0, 169, 169, 0.67) 71.78%);
        border-radius: 10px;
        padding-left: 15px;
        outline: none;
        border: none;
        width: 111px;
        height: 38px;
        right: 0;
        margin-right: 20px;
        margin-top: 25px;
        color: #fff;
        font-weight: bold;
    }
    .logo{
        width: 300px;
    }

    .header{
        background: radial-gradient(58.07% 96.96% at -2.43% 98.24%, rgba(120, 203, 250, 0.2) 0%, rgba(255, 0, 0, 0) 100%), radial-gradient(44.18% 71.1% at 67.81% 52.73%, #052228 0%, rgba(26, 26, 26, 0) 100%), linear-gradient(116.4deg, #000000 -0.07%, rgba(19, 19, 19, 0) 90.68%), linear-gradient(243.54deg, #2B0046 25.32%, #000000 45.16%);
        mix-blend-mode: normal;
        height: 2124px;
        padding: 20px 20px 0 20px;
        box-sizing: border-box;
    }

    .background{
        right: 0;
        top: 0;
        z-index: 0;
    }   

    .main{
        position: absolute;
        color: #fff;
        padding-top: 150px;
        width: 100%;
    }

    .main__title{
        font-style: italic;
        font-weight: normal;
        font-size: 60px;
    }


    .main__subtitle{
        font-weight: normal;
        font-size: 50px;
    }

    


</style>