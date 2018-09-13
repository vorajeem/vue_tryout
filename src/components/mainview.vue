<template>
  <div class="mainview border">
    Main  View Component - {{comment}}
    <spectrumview></spectrumview>
  </div>
</template>

<script>

import spectrumview from './spectrumview.vue';
export default {
  name: 'mainview',
  props: {
    comment: String
  },
  components: {
    spectrumview
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #4272b9;
}
</style>
