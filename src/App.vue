<template>
  <div id="app">
    <h1>Hola Mundo</h1>
    <img
      alt="Vue logo"
      src="https://img.wattpad.com/cover/258103381-352-k807196.jpg"
    />
    <HelloWorld msg="Hola Mundo" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
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
