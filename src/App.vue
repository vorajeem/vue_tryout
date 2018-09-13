<template> 
<!-- place html here -->
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <myheader></myheader>
    <!-- <button class=""></button> -->
    <div>
        <logocomponent></logocomponent>
    </div>
    <div>
      <unitselect></unitselect>
      <channelselect></channelselect>
    </div>
    <li><a href="www.instrotech.co.za">Instrotech.co.za</a></li>
      <mainview comment="Welcome to Your Vue.js App"></mainview>
    <myfooter></myfooter>
  </div>
</template>

<script>
// place JavaScript logic here
import mainview from './components/mainview.vue';
import myheader from './components/myheader.vue';
import myfooter from './components/myfooter.vue';
import channelselect from './components/channelselect.vue';
import unitselect from './components/unitselect.vue';
import logocomponent from './components/logocomponent.vue';

export default {
  name: 'app',
  props: {
    message: 'Start message'
  },
  components: {
    mainview,
    logocomponent,
    myheader,
    myfooter,
    channelselect,
    unitselect
  },
  methods: {
    
  }
}

</script>



/* place CSS here */
<style lang="scss">
@import './styles/custom-bootstrap.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #494d52;
  margin-top: 8px;
}

// .button {
//   border: none;
//   border-radius: 2px;
// }
</style>
