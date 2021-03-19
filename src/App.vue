<template>
  <div id="app">
    <h1 class="h1">{{ msg }}</h1>
    <h2>Lista de vacinas</h2>
    <br /><br />
    <p class="lead">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Impedit maxime
      autem, aut commodi at vel ratione. Animi doloribus amet odit possimus esse
      minima, accusamus quia dolorum laboriosam repellendus recusandae
      voluptatum qui quae optio autem provident perspiciatis. Dicta dolore
      voluptate sint?
    </p>

    <!-- BLOCKQUOTE WITH FOOTER -->
    <blockquote class="blockquote text-right">
      <p class="font-italic">"Vacina é tudo de bom!"</p>
      <footer class="blockquote-footer">
        Dona Almira
      </footer>
    </blockquote>

    <div></div>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Minha caderneta de vacinação"
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
