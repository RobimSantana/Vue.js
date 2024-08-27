<template>
    <div class="componente">
        <h1>Componente com Dados</h1>
        <p>Nome: {{nomeProduto}} - Codigo: {{codigoProduto}} </p>
    </div>

</template>


<style scoped>
 

</style>


<script setup>
const nomeProduto = 'Apontador'
const codigoProduto = '#987'

</script>

<!--<script>
// options API (forma mais antiga de do vue2)

//export default {
//  data:function(){
 //       return {
 //           nomeProduto: 'Caderno',
  //          codigoProduto: '#321'
   //     }
 //   }
//}




//Composition API ( forma mais nova de do vue3)

export default {
    setup: function(){
        const nomeProduto = 'Lapis'
        const codigoProduto = '#789'

        return {nomeProduto, codigoProduto}
    }
}

</script>
-->