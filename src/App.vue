<template>
  <div id="app">
    <FlixLoginBusca />
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
    // FlixChooseUser: () => import("./components/FlixChooseUser.vue"),
    FlixLoginBusca: () => import("./components/FlixLoginBusca.vue"),
    // FlixLogin: () => import('./components/FlixLogin.vue')
  }
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-decoration: none;
}
</style>
