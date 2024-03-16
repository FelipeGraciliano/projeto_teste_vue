<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
    export default{
        name: 'lifeCycle',
        data() {
            return {
                nome: 'Ainda não sei'
            }
        },
        created() {
            setTimeout(() =>{
                this.nome = 'Sextouu'
            }, 1000)
        },
        mounted() {
            this.nome = 'Estudando'
        }
    }
</script>