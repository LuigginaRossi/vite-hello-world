<script>
    import UserData from "./components/UserData.vue";

    export default{
        components: {UserData},
        data() {
            return {
                
            }
        },
    }
 
</script>

<template>
    <h1>La mia prima app con Vite!</h1>
        <!-- Bonus:
    Creare un secondo componente AppHero, che visualizza un jumbotron. -->
    <!-- npm i bootstrap -->
    <UserData></UserData>
</template>

<style scoped>

</style>
