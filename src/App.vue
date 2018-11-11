<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="/">Copelia A.</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <router-link to="/" class="nav-item nav-link">Inicio  |</router-link>
      </li>
      <li>
        <router-link to="/projects" class="nav-item nav-link">  Proyectos  |</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/contact" class="nav-item nav-link">  ¿Dónde?</router-link>
      </li>
    </ul>
  </div>
</nav>
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
