<template>
  <div id="app">
    <img
      alt="Telkom School"
      src="data:image/jpeg;base64,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"
    />
    <HelloWorld msg="WELCOME TO SMK TELKOM MAKASSAR" />
    <tombol msg="SELAMAT DATANG" class="btn btn-danger" /><br /><br />
    <komp />
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
</style>
