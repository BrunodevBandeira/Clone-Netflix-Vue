<template>
    <div id="FlixScreen">
        <main>
            <header class="header-movies">
                <div class="container">
                    <img class="container-logo" src="../sprite/netflix-logo.svg" alt="Logo Netflix">
                </div>
            </header>
            <section class="section-movies">
                <div class="container">
                    <div class="app-movies">
                        <h2 class="app-movies__title">Filmes, séries e muito mais. Sem limites.</h2>
                        <h3 class="app-movies__subtitle">Assista onde quiser. Cancele quando quiser.</h3>
                        <p class="app-movies__msg">Pronto para assistir? Informe seu email para criar ou reiniciar sua assinatura.</p>
                        <form class="form" method="GET">
                            <input type="text" placeholder="Buscar filme" name="movie" class="form__input" >
                            <input type="submit" class="form__submit" value="Vamos lá">
                        </form>
                    </div>
                    <ul class="app-movies-all" id="movies"></ul>
                </div>
            </section>
        </main>

        <section class="info-container"></section>
        <!-- <section class="info-container"></section>
        <section class="info-container"></section>
        <section class="info-container"></section>
        <section class="info-container"></section> -->
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

main {
    background-image:url('../assets/bg.jpg');
    background-repeat:no-repeat;
    background-size:cover;
    background-position:center;
    width:100%;
    height:100%;
}

main:after{
    background-color:rgba(0, 0, 0, 0.68);
    content:'';
    height:100%;
    left:0;
    top:0;
    width:100%;
}

.header-movies {
    float:left;
    position: relative;
    padding: 15px 0;
    width:100%;
    z-index: 9;
}
.header-movies__title {
    color:red;
    font-family:'arial',sans-serif;
    font-size:40px;
    text-shadow:2px 2px #000000;
}

.section-movies {
    align-items:center;
    display:flex;
    justify-content:center;
    padding-bottom:60px;
    width:100%;
}
.container {
    margin-left:auto;
    margin-right:auto;
    max-width:90%;
    padding-left:15px;
    padding-right:15px;
    width:100%;
}

.container-logo {
    width: 12rem;
    padding-top: 1rem;
}

.app-movies {
    align-items:center;
    display:flex;
    flex-direction:column;
    position:relative;
    margin: 60px 0;
    z-index:9;
}
.app-movies__title {
    color:white;
    font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;
    font-size:54px;
    max-width:70%;
    text-align:center;
}
.app-movies__subtitle {
    color:white;
    font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;
    font-size:25px;
    font-weight: 300;
    margin:20px 0 30px;
}
.app-movies__msg {
    color:white;
    font-size:18px;
    font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;
    margin-bottom: 20px;
}

.app-movies-all {
    display:grid;
    grid-gap:30px;
    grid-template-columns: repeat(auto-fit, 14.46%);
    position: relative;
    z-index: 9;
}

.app-movies-all__card {
    display: flex;
    flex-direction: column;
    position: relative;
    top: 0;
    transition: all .2s ease-in-out;
}
.app-movies-all__card:hover {
    top: -5px;
}

.app-movies-all__figure {
    height: 230px;
    box-shadow: 0 0px 9px 3px rgb(255,255,255,0.23);
}

.app-movies-all__thumb {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.app-movies-all__legend {
    display: flex;
    flex-direction: column;
}

.app-movies-all__year {
    color:rgba(255,255,255,0.76);
    font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;
    font-size:13px;
    background-color:#e50914;
    max-width:30px;
    padding: 4px 10px;
    line-height: 1;
    margin: 8px 0;
    border-radius: 2px;
}

.app-movies-all__title {
    color:white;
    font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;
    font-size:16px;
}

.form {
    display:flex;
    justify-content:center;
    width:100%;
}
.form__input {
    border: 0;
    background-color:#fff;
    border-radius:0;
    padding:15px 20px;
    width:35%;
}
.form__submit {
    background-color:#e50914;
    border:0;
    cursor:pointer;
    color:#fff;
    font-size:25px;
    padding:15px 30px;
    transition: all .2s ease-in-out;
}
.form__submit:hover {
    background-color:#c70913;
}

@media only screen and (max-width: 480px) {

    .app-movies {
        margin: 30px 0;
    }

    .header-movies__title {
        text-align: center;
    }

    .app-movies__title {
        font-size:40px;
        max-width:100%;
    }

    .app-movies__subtitle {
        text-align: center;
    }
    
    .app-movies__msg {
        text-align: center;
    }

    .form {
        overflow: hidden;
        flex-direction: column;
    }

    .form__input {
        width: 100%;
        margin-bottom: 5px;
    }

    .form__submit {
        font-size: 16px;
    }

    .app-movies-all {
        grid-gap:15px;
        grid-template-columns: repeat(auto-fit, 47%);
    }

    .app-movies-all__figure {
        height: 190px;
    }
}


section .info-container {
    width: 100%;
    height: 15rem;
    background: #000;
}
</style>