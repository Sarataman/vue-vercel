<template>
  <div id="app">
    <Dash class="mb-6" />
    <HelloWorld msg="Welcome to Your Vue.js App" class="text-center"/>
  </div>
</template>

<script>
import Dash from './components/Dash.vue'

export default {
  name: 'App',
  components: {
    Dash
  }
}
</script>

<style>
</style>
