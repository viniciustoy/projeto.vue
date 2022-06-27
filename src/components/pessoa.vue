<template>
  <div>
     <h2>Essa é a descrição da pessoa: {{ nome }} </h2>
  </div>
     <Info />
     <Form />
</template>
<script>
  import Info from './Info'
  import Form from './Form.vue'

  export default {
      name: 'Pessoa',
      components: {
         Info,
         Form 
         },
      data (){
          return{
            nome:'Marcos'
          }
      }
  }
</script>
