<template>
  <div id="app">
    <h1 class="h1">{{ msg }}</h1>
    <h2>Lista de vacinas</h2>
    <br /><br />
    <p class="lead">
      {{ mensagemPrincipal }}
    </p>

    <!-- RESPONSIVE ALIGN -->
    <p class="text-sm-right">
      {{ mensagemPrincipal }}
    </p>

    <!-- BLOCKQUOTE WITH FOOTER -->
    <blockquote class="blockquote text-right">
      <p class="font-italic">"Vacina é tudo de bom!"</p>
      <footer class="blockquote-footer">
        Dona Almira
      </footer>
    </blockquote>

    <br /><br />

    <!-- TURN BLOCK TO INLINE -->
    <h1 class="d-inline bg-success">Transformacao de Block em Inline</h1>

    <br />
    <br />

    <!-- TURN INLINE TO BLOCK -->
    <p>
      Teste de transformacao de<span class="d-block bg-primary">Inline</span> em
      bloco
    </p>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Minha caderneta de vacinação",
      mensagemPrincipal:
        "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit maxime utem " +
        "aut commodi at vel ratione. Animi doloribus amet odit possimus esse " +
        "minima, accusamus quia dolorum laboriosam repellendus recusandae " +
        "voluptatum qui quae optio autem provident perspiciatis. Dicta dolore " +
        "voluptate sint?"
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
