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
            <!-- <form class="form__submit">
                <input  class="form__input" type="email" value="Email"> 
                <button class="btn form__submit" >Vamos lá <i class="fa fa-angle-right"></i></button>
                <input type="submit" class="form__submit" value="Vamos lá">
            </form> -->

            <form class="form" method="GET">
                <input type="text" placeholder="Buscar filme" name="movie" class="form__input" >
                <input type="submit" class="form__submit" value="Vamos lá">
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


        <section class="containeres">
                <h1 class="container-title"> Perguntas Frequentes </h1>
            <div>
                <div class="mini-container"> 
                    <p>O que é a Netflix ?</p><i class="fa fa-plus fa-2x"></i>
                </div>
                <div class="sub-container">
                    <p>A Netflix é um serviço de transmissão online que oferece uma ampla variedade de séries, filmes e documentários premiados em milhares de aparelhos conectados à internet.
                    <br><br>
                    Você pode assistir a quantos filmes e séries quiser, quando e onde quiser, sem comerciais – tudo por um preço mensal bem acessível. Aqui você sempre encontra novidades. A cada semana, adicionamos novas séries e filmes.</p>
                </div>
            </div>
                <!-- <i class="fa fa-times" aria-hidden="true"></i> -->
            <div>
                <div class="mini-container"> 
                    <p>Quanto custa a Netflix ?</p><i class="fa fa-plus fa-2x"></i>
                </div>
                <div class="sub-container">
                    <p>Assista à Netflix no seu celular, tablet, Smart TV, notebook ou aparelho de streaming por uma taxa mensal única. Os planos variam de R$25,90 a R$55,90 por mês. Sem contrato nem taxas extras.</p>
                </div>
            </div>

            <div>
                <div class="mini-container"> 
                    <p>Onde posso assistir ?</p><i class="fa fa-plus fa-2x"></i>
                </div>
                <div class="sub-container">
                    <p>Assista onde quiser, quando quiser. Faça login com sua conta Netflix em netflix.com para começar a assistir no computador ou em qualquer aparelho conectado à Internet compatível com o aplicativo Netflix, como Smart TVs, smartphones, tablets, aparelhos de streaming e videogames.
                    <br><br>
                    Você também pode baixar a sua série favorita com o aplicativo Netflix para iOS, Android ou Windows 10. Use downloads para levar a Netflix para onde quiser sem precisar de conexão com a Internet. Leve a Netflix com você para qualquer lugar.</p>
                </div>
            </div>

            <div>
            <div class="mini-container"> 
                    <p>Como faço para cancelar ?</p><i class="fa fa-plus fa-2x"></i>
                </div>
                <div class="sub-container">
                    <p>A Netflix é flexível. Não há contratos nem compromissos. Você pode cancelar a sua conta na internet com apenas dois cliques. Não há taxa de cancelamento – você pode começar ou encerrar a sua assinatura a qualquer momento.</p>
                </div>
            </div>

            <div>
                <div class="mini-container"> 
                    <p>Oque eu posso assistir na Netflix ?</p><i class="fa fa-plus fa-2x"></i>
                </div>
                <div class="sub-container">
                    <p>A Netflix tem um grande catálogo de filmes, documentários, séries, originais Netflix premiados e muito mais. Assista o quanto quiser, quando quiser.</p>
                </div>
            </div>

            <div>
                <div class="mini-container"> 
                    <p>A Netflix é adequada para crianças ?</p><i class="fa fa-plus fa-2x"></i>
                </div>
                <div class="sub-container">
                    <p>A experiência infantil da Netflix faz parte da sua assinatura para que as crianças se divirtam em seu próprio espaço com séries e filmes familiares sob a supervisão dos pais.
                    <br><br>
                    O recurso de controle dos pais, incluso nos perfis para crianças e protegido por PIN, permite restringir a classificação etária do conteúdo que as crianças podem ver e bloquear títulos específicos que você não quer que elas assistam.</p>
                </div>
            </div>

        <nav class="">
            <p class="p-title"> Pronto para assistir? Informe seu email para criar ou reiniciar sua assinatura.</p>
            <form class="form" method="GET">
                <input type="text" placeholder="Buscar filme" name="movie" class="form__input" >
                <input type="submit" class="form__submit" value="Vamos lá">
            </form>
        </nav>
        </section>
        

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
    function handler(e) {
    //Esse evento, não mostra a URL passada no rash
        e.preventDefault();
        let movie = document.querySelector(".form__input").value;
        if(movie) {
            const _url = `https://www.omdbapi.com/?s=${movie}&apikey=ead5319b`;
            const _options = {
                method: "GET",
                mode: "cors",
                redirect: "follow",
                cache: "default"
            }

            fetch(_url, _options).then(function(response) {
                //Tratamento de erro
                if(!response.ok) throw new Error("Erro ao executar a requisição");
                
                //Retorno do Objeto no formado JSON
                return response.json();
                
            })

            //Receber dados

            .then(function(data){
                let newContent = "";
                for(let index = 1; index < data.Search.lengtn; index++) {
                    newContent += `<li class="app-movies-all__card">`;

                            newContent += `<figure class="app-movies-all__figure">`; 
                                newContent += `<img class="app-movies-all__thumb" src="${data.Search[index].Poster}">`;
                            newContent += `</figure>`;

                        newContent += `<legend class="app-movies-all__legend">`;
                            newContent += `<span class="app-movies-all__year">${data.Search[index].Year}</span>`;
                            newContent += `<h2 class="app-movies-all__title">${data.Search[index].Title}</h2>`; 
                        newContent += `</legend>`;
                    newContent += `</li>`;
                }

                document.getElementById("movies").innerHTML = newContent;

            })
        }
    }

    window.onload =() => {
        const submit = document.querySelector(".form__submit")
        submit.addEventListener("click", handler);
    }
</script>


<style scoped>

    #flb {
        width: 100%;
        height: 474vh;
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

    .form__submit  {
        width: 12rem;
        height: 4.7rem;
        border: none;
        background: #e50914;
        color: #fff;
        font-size: 1.6rem;
        cursor: pointer;
    }

    .form__submit:hover {
            background-color:#c70913;
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

    .containeres {
        width: 100%;
        height: 52rem;
        background: #000;
        margin: 0.5rem 0; 
        color: #fff;
    }

    .container-title {
        font-size: 3.125rem;
        padding: 4.5rem 0 2rem 0;
        text-align: center;
    }

    .mini-container {
        background: #303030;
        width: 48rem;
        height: 4.2rem;
        position: relative;
        left: 28rem;
        display: flex;
        justify-content: center;
        justify-content: space-between;
        margin: 0.5rem 0;
    }

    .mini-container p {
        padding: 1.4rem 0 0 1.2rem;
        font-size: 1.5rem;
        font-weight: bolder;
    }

    .mini-container .fa-plus {
        padding: 1.4rem 1.2rem 0 0;
    }

    .sub-container {
        background: #303030;
        width: 48rem;
        height: 18rem;
        position: relative;
        left: 28rem;
        display: flex;
        margin-top: 0.1rem;
        font-size: 1.625rem;
        font-weight: 400;
        padding: 1.2rem;
        display: none;
    }

    .sub-container.mostrar {
        display: block;
    }


    footer {
        width: 100%;
        height: 15rem;
        background: #000;
        margin-top: 0.5rem; 
        color: #fff;
    }


    /* footer {
        width: 100%;
        height: 19.8rem;
        background-color: rgba(0,0,0,.75);
        position: absolute;
        bottom: -29rem;
    } */

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