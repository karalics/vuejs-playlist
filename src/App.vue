<template>
  <div>
   <h1>{{ title }}</h1>
   <h2>NAMES</h2>
   <names></names>
   <h2>CITIES</h2>
   <cities></cities>
  </div>
</template>

<script>
import Cities from './Cities.vue'


export default {
  components: {
    'cities': Cities
  },
  data () {
    return {
      title: 'My First Vue.js App'
    }
  }
}
</script>

<style>

</style>
