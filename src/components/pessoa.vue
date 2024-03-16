<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
        <p>Estou trabalhando no momento</p>
        <p>Utilizo as seguintes tecnologias:</p>

        <ul>
            <li>HYML</li>
            <li>PHP</li>
            <li>Vue</li>
        </ul>
    </div>
</template>

<script>

    export default {
        name: 'pessoa',
        data() {
            return{
                nome: 'Santos'
            }
        }
    }
</script>