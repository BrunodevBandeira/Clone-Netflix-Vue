<template>
    <div id="flb">
        <header>
            <!-- <select class="footer-idioma">
                <option class="footer-texto" selected> Português </option>
                <option class="footer-texto" > Inglês </option>
            </select> -->

                <img class="logo" src="../sprite/netflix-logo.svg" alt="Logo da Netflix">
                <button class="header-btn"> Entrar </button>
        </header>

        <img class="telaDeFundo" src="../assets/Netflix.jpg" alt="Tela de fundo">

        <nav class="main-input">
            <form>
                <input type="email" value="Email"> <button class="btn" >Vamos lá <i class="fa fa-angle-right"></i>
</button>
            </form>
        </nav>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

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
        width: 10rem;
        height: 5rem;
        margin: 0.2rem 0 0 3rem;
        position: absolute;
        z-index: 5;
    }

    .telaDeFundo {
        width: 100vw;
        height: 110vh;
        position: relative;
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
</style>