<template>
    <h1>Meu nome é: {{name}} </h1>
</template>

<script>
   export default {
       name: 'LifeCycle',
       data() {
           return{ 
             name: 'ainda nao sei'
          }
       },
        created (){
            setTimeout (()=> {
                this.name = 'Marcos'
            }, 2000)
         },
        mounted(){
           setTimeout (() =>{
               this.name = 'O men'
           }, 3000) 
        }
   }
</script>
