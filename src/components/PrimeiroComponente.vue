<template>
    <div>
        <h1>Olá, Vue!!</h1>
        <p>Meu nome e {{ name }} tenho {{ age }} anos e hobbies como {{ hobbies[0] }} e {{ hobbies[1] }} !!</p>
    </div>
</template>

<script>
    export default 
    {
        name: 'PrimeiroComponente',
        data(){
            return {
                name: 'Felipe',
                age: 25,
                hobbies: ['Ler', 'Escrever']
            }
        }
    }
</script>