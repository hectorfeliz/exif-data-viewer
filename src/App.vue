<template>
  <div id="app">
    <intro/>
  </div>
</template>

<script>
import intro from './components/intro.vue'

export default {
  name: 'App',
  components: {
    intro
  }
}
</script>

<style lang="scss">
@import '/styles/main.css';
</style>
