<template>
   <Pcomponente />
   <LifeCycle />
   <Pessoa />

</template>

<script>
    import Pcomponente from './components/p_componente.vue'
    import LifeCycle from './components/LifeCycle.vue'
    import Pessoa from './components/pessoa.vue'

    export default {
      name: 'App',
      components: {
          Pcomponente,
          LifeCycle,
          Pessoa
      }
    }

</script>