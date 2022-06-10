<template>
    <div>
       <h1> Óla vue!</h1>
       <p> Meu nome é {{ nome }} e trabalho como {{ profissao }}</p>
    </div>
</template>

<script>
   export default {
       name: 'Pcomponente',
       data() {
           return{
               nome:"Marcos",
               profissao:"programador"
           }
       }
   }
</script>
