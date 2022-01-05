<template>
    <div id="flb">
        <header>
                                    <select class="footer-idioma">
                            <option class="footer-texto" selected> Português </option>
                            <option class="footer-texto" > Inglês </option>
                        </select>
                <img class="logo" src="../sprite/netflix-logo.svg" alt="Logo da Netflix">
        </header>

        <img class="telaDeFundo" src="../assets/Netflix.jpg" alt="Tela de fundo">

    </div>
</template>

<script>
export default {
    
}
</script>

<style >
    header .logo {
        width: 10rem;
        height: 5rem;
        margin: 0.2rem 0 0 3rem;
        position: absolute;
        z-index: 5;
    }


    .telaDeFundo {
        width: 100vw;
        height: 160vh;
        position: relative;
    }
</style>