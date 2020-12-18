<template>
  <div id="app">
    <vue-header></vue-header>
    <vue-body></vue-body>
    <img alt="Vue logo" src="./assets/logo.png">
    <vue-footer>Footer</vue-footer>

   
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import VueHeader from "./components/Header.vue";
import VueBody from "./components/Body.vue";
import VueFooter from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
    VueHeader,
    VueBody,
    VueFooter,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1066bd;
  margin-top: 60px;
}
</style>
