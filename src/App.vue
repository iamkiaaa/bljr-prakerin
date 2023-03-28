<template>
  <div id="app">
    <img
      alt="Telkom School"
      src="data:image/png;base64,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"
    />
    <HelloWorld msg="WELCOME TO SMK TELKOM MAKASSAR" />
    <komp />
    <tombol msg="SELAMAT DATANG" class="btn btn-danger" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import tombol from './components/tombol.vue';
import komp from './components/komp.vue';
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap.js';

export default {
  name: 'App',
  components: {
    HelloWorld,
    tombol,
    komp,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img{
  width: 100px;
}
</style>
