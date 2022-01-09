<template>
    <div id="chooserUser">
        <header>
            <img class="logo" src="../sprite/netflix-logo.svg" alt="Logo da Netflix">
        </header>

        <nav>
            <h1 class="title">Quem está assistindo ?</h1>
            <div class="login-users"></div>
        </nav>
    </div>
</template>


<script>
export default {
    
}
</script>


<style scoped>

    #chooserUser {
        background-color: #141414;
        width: 100vw;
        height: 100vh;
    }

    .logo {
        width: 10rem;
        height: 5rem;
        margin: 0.2rem 0 0 3rem;
        position: absolute;
        z-index: 5;
    }

    nav {
        position: absolute;
        top: 30%;
        left: 34.5%;
    }
    
    nav .title {
        padding: 1rem 1rem;
        color: #fff;
        font-size: 4rem;
    }

    nav .login-users {
        background: lightpink;
        width: 10rem;
        height: 10rem;
    }

</style>