<template lang="html">
<div class=" border border-info">
Channel select:
<button type="button" class="btn btn-default" v-for="channel in channels">Ch :{{channel}}</button>
<!-- <ul align="left">
  <li v-for="channel in channels">{{channel}}</li>
</ul> -->

</div>

</template>

<script lang="js">
  export default  {
    name: 'channelselect',
    props: [],
    mounted() {

    },
    data() {
      return {
          channels:['1','2','3','4','5','6','7','8','9','10','11','12','13','14','15','16','17']
      }
    },
    methods: {

    },
    computed: {

    }
}
</script>

<style scoped lang="scss">
  .channelselect {

  }
</style>
