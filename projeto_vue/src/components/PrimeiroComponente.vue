<template>
    <div>
        <h1>Olá mundo!</h1>
        <p>Meu nome é {{ nome }}</p>
    </div>
  </template>
  
  <script>

    export default {
      name: 'PrimeiroComponente',
      data(){
        return {
            nome: "Caio",
            profissao: "Programador"
        }
      }
    }
  </script>