<template>
  <div>
   <h1>{{ title }}</h1>
   <p>{{ greeting() }}</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'My First Vue.js App'
    }
  },
  methods: {
    greeting: function(){
      return "Hello World.";
    }
  }
}
</script>

<style>

</style>
