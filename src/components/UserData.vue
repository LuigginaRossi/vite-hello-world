<script>
    export default {
        data () {
            return{
                name: "Michelangelo",
                surname: "Da Vinci",
            }
        },
        methods: {
            fullname(){
                return this.name + this.surname;
            }
        },      
    }
</script>

<template>
    <div>
        <h3>Benvenuto {{fullname()}}</h3>
    </div>
</template>

<style>

</style>