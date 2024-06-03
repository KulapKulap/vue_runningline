<template>
  <div id="app">
    <RunningLine/>


  </div>
</template>

<script>
import RunningLine from './components/RunningLine.vue';

export default {
  name: 'App',
  components: {
    RunningLine
  }
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
