<template lang="html">

<div class="border border-success">

  <div class="btn-group" role="group" aria-label="...">
  Unit select: 
  <button type="button" class="btn btn-default" v-for="unit in units">Unit: {{unit}}</button>
</div>

</div>

</template>

<script lang="js">
  export default  {
    name: 'unitselect',
    props: [],
    mounted() {

    },
    data() {
      return {
        units: ['1','67']

      }
    },
    methods: {

    },
    computed: {

    }
}
</script>

<style scoped lang="scss">
  .unitselect {

  }
</style>
