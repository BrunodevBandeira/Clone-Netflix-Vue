<template>
    <div id="flb">
        <header>
            <img class="logo" src="../sprite/netflix-logo.svg" alt="Logo da Netflix">
            <button class="header-btn"> Entrar </button>
        </header>

        <img class="telaDeFundo" src="../assets/Netflix.jpg" alt="Tela de fundo">

        <nav class="main-input">
            <h1 class="title">Filmes, séries e muito  <br>mais. Sem limites.</h1>
            <h3 class="sub-title">Assista onde quiser. Cancele quando quiser.</h3>
            <p class="p-title">Pronto para assistir? Informe seu email para criar ou reiniciar sua assinatura.</p>
            <form class="form__submit">
                <input  class="form__input" type="email" value="Email"> 
                <button class="btn" >Vamos lá <i class="fa fa-angle-right"></i></button>
            </form>
        </nav>

        <section class="container">

            <div class="info-container">
                <h1 class="title-container">Aproveite na TV.</h1>
                <p class="p-container">Assista em Smart TVs, PlayStation, Xbox, Chromecast, Apple TV, aparelhos de Blu-ray e outros dispositivos.</p>
            </div>

            <div class="icon-container">
                <div class="icon-content"></div>
                <i class="fa fa-laptop"></i>

            </div>

        </section>

        <section class="container"></section>

        <section class="container">
                        <div class="info-container">
                <h1 class="title-container">Assista quando quiser.</h1>
                <p class="p-container">Assista no celular, tablet, Smart TV ou notebook sem pagar a mais por isso..</p>
            </div>

            <div class="icon-container">
                <div class="icon-content"></div>
                <i class="fa fa-desktop"></i>

            </div>
        </section>
        <section class="container"></section>
        <section class="container"></section>

        <footer>
            saspm
        </footer>
    </div>
</template>

<script>

</script>

<style scoped>

    #flb {
        width: 100%;
        height: 430vh;
        background: #222;
    }

    .header-btn {
        background-color: #e50914;
        padding: 0.8rem 1.5rem;
        font-size: 1rem;
        border-radius: 0.2rem;
        color: #fff;
        position: absolute;
        z-index: 5;
        left: 90%;
        margin: 2rem 0 0 1rem;
        border: none;
    }

    header .logo {
        width: 15rem;
        height: 8rem;
        margin: 0.2rem 0 0 3rem;
        position: absolute;
        z-index: 5;
    }

    .telaDeFundo {
        width: 100vw;
        height: 100vh;
        position: relative;
        filter: brightness(0.4);
    }

    .main-input {
        margin: -8rem 0;
    }

    .main-input .title {
        color: #fff;
        text-align: center;
        font-size: 4.125rem;
        font-weight: bolder;
    }

    .main-input .sub-title {
        color: #fff;
        text-align: center;
        font-size: 2.125rem;
        padding: 1.5rem;
        font-weight: bolder;
    }


    .main-input .p-title {
        color: #fff;
        text-align: center;
        padding: 1rem;
        font-weight: bolder;
        
    }


    .main-input {
        position: absolute;
        top: 50%;
        left: 30%;
    }

    form {
        width: 44rem;
        height: 4.8;
        display: flex;
    }

    form input {
        width: 32rem;
        height: 4.8rem;
        font-size: 1.2rem;
        color: #8c8c8c;
        padding: 10px;
    }

    .btn {
        width: 12rem;
        height: 4.7rem;
        border: none;
        background: #e50914;
        color: #fff;
        font-size: 1.6rem;
        cursor: pointer;
    }


    .container {
        width: 100%;
        height: 29.2rem;
        background: #000;
        margin: 0.5rem 0; 
        color: #fff;
        display: flex;
        justify-content: center;
        align-content: center;
    }

    .info-container {
        width: 50%;
    }

    .title-container {
        text-align: center;
        font-size: 3.125rem;
        line-height: 1.1;
        margin-bottom: 0.5rem;
        position: relative;
        top: 28.5%;
    }

    .p-container {
        font-size: 1.625rem;
        font-weight: 400;
        padding: 0 2rem 0 15rem;
        position: relative;
        top: 28.5%;
    }

    .icon-container {
        width: 50%;
    }

    .icon-container .fa {
        font-size: 25rem;
        position: relative;
        left: 8%;
        top: -5%;
    }

    .icon-content {
        background: #e509ae;
        width: 5rem;
        height: 5rem;
    }

    footer {
        width: 100%;
        height: 15rem;
        background: #000;
        margin-top: 0.5rem; 
        color: #fff;
    }


</style>