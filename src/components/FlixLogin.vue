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
                <p class="sub-title2">Precisa de Ajuda</p>
                <p class="sub-title3"><i class="fa fa-facebook-square"></i> Conectar com Facebook</p>
                <p class="sub-title"> Novo por aqui ?<span>Assine agora.</span></p>
                <p class="sub-title">Essa página é protegida pelo google reCAPTCHA <br>
                para garantir que vc não é um robo <a href="#"> saiba mais</a>
                </p>
            </div>
        </nav>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style>

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
        height: 120vh;
        opacity: 0.5;
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
        color: #fff;
    }

    .login-box .sub-title2 {
        color: #fff;
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }

    .login-box .sub-title3 {
        color: #fff;
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

</style>