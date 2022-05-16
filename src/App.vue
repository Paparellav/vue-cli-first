<template>
  <MyTitle />
  <MyJumbo />
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import MyTitle from './components/MyTitle.vue';
import MyJumbo from './components/MyJumbo.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyTitle,
    MyJumbo
  }
}
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
