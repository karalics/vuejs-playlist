<template>
  <ul>
    <li v-for="city in cities">{{ city }}</li>
  </ul>
</template>

<script>
export default {
  data () {
    return {
      cities: ['Berlin', 'Zurich', 'Belgrade', 'Bern']
    }
  }
}
</script>

<style>

</style>
