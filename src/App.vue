<template>
  <div id="app">
    <MyTitle/>
    <jumboTron/>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import jumboTron from './components/jumboTron.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    jumboTron,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  overflow: hidden;
}
</style>
