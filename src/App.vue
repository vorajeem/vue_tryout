<template> 
<!-- place html here -->
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <mainview comment="Welcome to Your Vue.js App"/></mainview>
    <spectrumview>
      <mainview comment="salaam"></mainview>
    </spectrumview>
    <!-- <button v-on:click="myClickHandler">Click ekse</button> -->
    <!-- <button v-on:click="changeMessage">Click me!</button> -->
  </div>
</template>

<script>
// place JavaScript logic here
import mainview from './components/mainview.vue';
import spectrumview from './components/spectrumview.vue';
export default {
  name: 'app',
  props: {
    message: 'Start message'
  },
  components: {
    mainview,
    spectrumview
  },
  methods: {
    
  }
}

</script>

<style>
/* place CSS here */
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
