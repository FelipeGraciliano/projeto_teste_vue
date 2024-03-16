<template>
  <div>
  <PrimeiroComponente />
  <lyfeCycle />
  <pessoa />

</div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue';
  import lyfeCycle from './components/lyfeCycle.vue';
  import pessoa from './components/pessoa.vue';
  
  export default 
    {
      name: 'App',
      components: {
          PrimeiroComponente,
          lyfeCycle,
          pessoa
      }
      
    }
</script>