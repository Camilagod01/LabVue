<script setup>
import Counter from './components/Counter.vue'
import Question from './components/Question.vue';


function mostrarMensaje(msj){
  alert(msj)

}

</script>

<template>

  <h1>Mi contador</h1>
  <Counter :value="15" @send="mostrarMensaje" />

  <Question></Question>

 

</template>