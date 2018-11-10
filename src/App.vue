<template>
  <div id="app">
    <div class="nav">
      <a class="navbar-brand">Copelia Altamirano</a>
      <ul class="links-list .ml-5">
      <router-link to="/">Inicio  |</router-link>
      <router-link to="/about">  ¿Quién?  |</router-link>
      <router-link to="/contact">  ¿Dónde?</router-link>
      </ul>
    </div>
    <router-view/>
  </div>
</template>

<style>
.nav{
  font-family: 'Cabin Sketch';
  color: #42b983;
  padding: 30px;
}
.navbar-brand{
  font-size: 2em;
}
  a{
    font-weight: bold;
    color: #42b983;
    font-size: 1.5em;
  } 
  .links-list{
    align-content:flex-end;
  } 
  .router-link-exact-active{
    color: #484B3E;
  }
  a:hover{
    color: #484B3E;
  }

  @media screen and (max-width: 375px) {
  a{
    font-size: 20px;
  }
  }
</style>
