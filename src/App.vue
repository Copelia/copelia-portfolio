<template>
  <div id="app">
    <div class="nav" id="nav" style="font-family: 'Cabin Sketch'">
      <router-link to="/">Inicio</router-link> |
      <router-link to="/about">¿Quién?</router-link> |
      <router-link to="/contact">¿Dónde?</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="stylus">
.nav
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align right
  color #2c3e50
  padding 30px
  a
    font-weight bold
    color #2c3e50
    font-size 2em
    &.
      router-link-exact-active
      color #42b983
</style>
