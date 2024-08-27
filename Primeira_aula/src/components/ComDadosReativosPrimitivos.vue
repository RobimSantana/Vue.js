<template>

    <div class="componente">
        <h1>Componente com Dados Reativos</h1>
        <p>Nome: {{nome}} | idade: {{idade}} </p>
        <button @click="fazAniversario">Fazee Aniversario</button>
        <button @click="mudarNome">Mudar Nome</button>
    </div>    

</template>

<script setup>
import { ref } from 'vue'
    const nome = ref("Robim")
    const idade = ref(30)

    function fazAniversario(){
        idade.value +=1
    }

    function mudarNome(){
        nome.value = 'Robim Santana'
                    
    }


</script>

