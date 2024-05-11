<template>
  <FaceGenerator />
  <Buttons />
</template>

<script>
import FaceGenerator from './views/FaceGenerator.vue'
import Buttons from './components/Buttons.vue'

export default {
  components: { FaceGenerator, Buttons },
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
