<!-- src/App.vue -->
<template>
  <div id="app">
    <AppFooter></AppFooter>
    <router-view></router-view>
  </div>
</template>

<script>
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppFooter,
  }
}
</script>

<style scoped>
/* Scoped styles for App.vue */
</style>
