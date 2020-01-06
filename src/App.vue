<template>
  <div id="app">
    <users/>
  </div>
</template>

<script>
import users from './components/users.vue'

export default {
  name: 'app',
  components: {
    users
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
