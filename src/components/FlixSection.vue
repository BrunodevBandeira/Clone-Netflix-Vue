<template>
    <div id="FlixLoginBusca">
        <FlixLoginBusca />
    </div>
</template>


<script>
export default {
    name: "FlixLoginBusca",
    component: {
        FlixLoginBusca: ()=> import("./FlixLoginBusca.vue")
    }
}
</script>


<style scoped>
    
</style>