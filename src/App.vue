<template>
  <div id="app">
    <FlixFooter />

  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
    FlixFooter: () => import("./components/FlixFooter.vue"),
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
