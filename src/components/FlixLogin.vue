<template>
    <div id="container-login">
        <header>
                <img class="logo" src="../sprite/netflix-logo.svg" alt="Logo da Netflix">
        </header>

        <img class="telaDeFundo" src="../assets/Netflix.jpg" alt="Tela de fundo">

        <nav class="login-box">
            <div class="login-box-over">
                <h1 class="title"> Entrar </h1>
                <form class="inputs">
                    <input class="box" type="text" placeholder="Email ou número de telefone">
                    <input class="box" type="text" placeholder="Senha">
                </form>
                <button class="btn"> Entrar </button>

                <p class="sub-title"><input type="checkbox"> Lembre-se de mim </p>

                <p class="sub-title2"><a href="#"> Precisa de Ajuda ? </a></p>

                <p class="sub-title3"><i class="fa fa-facebook-square"></i><a href="https://www.facebook.com/" target="_blank"> Conectar com Facebook </a></p>

                <p class="sub-title4"> Novo por aqui ?<span> <a href="#"> Assine agora. </a></span></p>
                
                <p class="sub-title5">Essa página é protegida pelo google reCAPTCHA <br>
                para garantir que vc não é um robo <a href="#"> saiba mais</a>
                </p>
            </div>
        </nav>

        <footer>
            <div class="footer-painel">
                    <div class="footer-links-c1">
                        <a href="#">Dúvidas? Ligue 0800-761-4631</a>
                        <br>
                        <a href="#">Perguntas frequentes</a>
                        <br>
                        <a href="#">Preferências de cookies</a>

                        <select class="footer-idioma">
                            <option class="footer-texto" selected> Português </option>
                            <option class="footer-texto" > Inglês </option>
                        </select>
                    </div>

                    <div class="footer-links-c2">
                        <a href="#">Centro de ajuda</a>
                        <br>
                        <a href="#">Informações corporativas</a>
                    </div>

                    <div class="footer-links-c3">
                        <a href="#">Termos de uso</a>
                    </div>

                    <div class="footer-links-c4">
                        <a href="#">Privacidade</a>
                    </div>

            </div>
        </footer>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

    #container-login {
        background: #141414;
    }

    .logo {
        width: 10rem;
        height: 5rem;
        margin: 0.2rem 0 0 3rem;
        position: absolute;
        z-index: 5;
    }


    .telaDeFundo {
        width: 100vw;
        height: 160vh;
        opacity: 0.5;
        position: relative;
    }

    .login-box {
        width: 32.5rem;
        height: 45rem;
        background-color: rgba(0,0,0,.75);
        position: absolute;
        left: 38rem;
        bottom: -3rem;
    }

    .login-box-over {
        position: relative;
        left: 4.6rem;
        top: 4rem;
        width: 23.5rem;
        height: 30rem;
    }

    .login-box-over .btn {
        border-radius: 4px;
        font-size: 1.2rem;
        font-weight: 700;
        background: #e50914;
        text-align: center;
        width: 23.5rem;
        height: 3.2rem;
        color: #fff;
        border: none;
    }

    .login-box .inputs {
        padding: 2rem 0;
    }

    .login-box .inputs .box {
        padding: 0 1.2rem;
    }

    .login-box .box {
    margin: 1rem 0;
    border-radius: 4px;
    border: 0;
    color: #fff;
    height: 50px;
    padding: 16px 0;
    background: #333333;
    width: 23.5rem;
    
    }


    .login-box .title {
        color: #fff;
        font-size: 1.8rem;
        font-weight: 700;
    }

    .login-box .sub-title {
        color: #8c8c8c;
        position: absolute;
    }

    .login-box .sub-title2 {
        color: #8c8c8c;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        padding-top: 1rem;
    }

    .login-box .sub-title2 a{
        color: #8c8c8c;
    }

    .login-box .sub-title3 {
        color: #8c8c8c;
        margin-bottom: -5px;
    }

    .login-box .sub-title3 a{
        color: #8c8c8c;
    }


    .login-box .sub-title4 {
        color: #8c8c8c;
        padding-top: 1.5rem;
    }

    .login-box .sub-title4 span{
        color: #fff;
        font-size: 1.2rem;
        font-family: bolder;
    }

    .login-box .sub-title4 span a{
        color: #fff;

    }

    .login-box .sub-title5 {
        color: #8c8c8c;
        padding: 0.9rem 0;
        font-size: 0.8rem;
    }

    .login-box .sub-title5 a{
        color: #0071eb;
    }


    .login-box .sub-title input{
        border-radius: 2px;
        height: 16px;
        left: -20px;
        width: 16px;
        margin: 1rem 0 0 0;
    }

    .login-box .fa {
        color: #3b5998;
        padding: 2rem 0 0 0;
        font-size: 1.8rem ;
    }

    footer {
        width: 100%;
        height: 19.8rem;
        background-color: rgba(0,0,0,.75);
        position: absolute;
        bottom: -29rem;
    }

    footer div a{
        color: #8c8c8c;
    }


    .footer-painel{
        padding: 2.5rem;
        display: flex;
        justify-content: space-evenly;
    }

    .footer-idioma  {
        width: 45%;
        height: 25%;
        padding: 10px 15px;
        border: 1px solid #333;
        border-radius: 4px;
        background-color: #000;
    }

    .footer-links-c1 {
        width: 300px;
        display: flex;
        flex-direction: column;
    }

    .footer-links-c1 a{
        padding: 0.8rem 0;
        display: flex;
        flex-direction: column;
    }

    .footer-links-c2 {
        width: 300px;
    }

    .footer-links-c2 a{
        padding: 0.2rem 0;
        display: flex;
        flex-direction: column;
    }

    .footer-links-c3 {
        width: 300px;
    }

    .footer-links-c3 a{
        padding: 0.8rem 0;
        display: flex;
        flex-direction: row;
    }

    
</style>