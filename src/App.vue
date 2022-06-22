<template>
   <Pcomponente />
   <LifeCycle />
</template>

<script>
    import Pcomponente from './components/p_componente.vue'
    import LifeCycle from './components/LifeCycle.vue'

    export default {
      name: 'App',
      components: {
          Pcomponente,
          LifeCycle
      }
    }

</script>