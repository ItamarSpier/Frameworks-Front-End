<template>
    <div>
        <h1>SPIER INFORMATICA</h1>
    <p>Meu nome é {{ nome }} e sou {{  profissao }} e {{ profissao2 }}</p>
    </div>
</template>

<script>
    export default {
      name: 'PrimeiroComponente',
      data() {
        return {
            nome: "Itamar",
            profissao: "TI",
            profissao2: "programador"
        }
      }
    }
</script>