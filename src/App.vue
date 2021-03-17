<template>
  <div id="app">
    <img src="./assets/logo.png" />
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <div>
      <div>
        <b-button-group>
          <b-button>Button 1</b-button>
          <b-button>Button 2</b-button>
          <b-button>Button 3</b-button>
        </b-button-group>
      </div>
      <div class="mt-3">
        <b-button-group>
          <b-button variant="success">Success</b-button>
          <b-button variant="info">Info</b-button>
          <b-button variant="warning">Warning</b-button>
        </b-button-group>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
    };
  },
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
