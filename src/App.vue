<template>
  <div id="app">
    Demonstrating the broken Sass import of a CSS file.
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style lang="sass">
@import '~hint.css/hint.base.css'
#app
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px
</style>
