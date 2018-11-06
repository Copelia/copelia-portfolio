<template>
  <div id="app">
    <div class="nav" id="nav" style="font-family: 'Cabin Sketch'">
      <router-link to="/">Inicio</router-link> |
      <router-link to="/about">¿Quién?</router-link> |
      <router-link to="/contact">¿Dónde?</router-link>
    </div>
    <div class="header">
      <h4>Copelia Altamirano</h4>
      <h5>Front-end Developer</h5>
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
  .router-link-exact-active
    color #42b983
    
 .header{
     text-align: right;
     margin-bottom: 0.5em;
     font-size: 4em;
     color: #373D3F;
  }  
</style>
