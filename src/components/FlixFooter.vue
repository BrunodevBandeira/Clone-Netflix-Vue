<template>
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
</template>


<script>

</script>


<style >
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