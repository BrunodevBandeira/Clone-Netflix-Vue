<template>
  <div id="app">
    <FlixLogin />
  </div>
</template>

<script>
  
export default {
  name: 'app',
  components: {
    FlixLogin: () => import('./components/FlixLogin.vue')
  }
}
</script>

<style>
#app {
}


* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-decoration: none;
}

root {
  vermelho: #e50914;
}

</style>
