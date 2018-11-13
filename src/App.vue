<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="/">Copelia Altamirano</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li>
      <!-- <li class="nav-item">
        <router-link to="/" class="nav-item nav-link">Inicio  |</router-link>
      </li> -->
        <router-link to="/projects" class="nav-item nav-link">  Proyectos  |</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/contact" class="nav-item nav-link">  Redes</router-link>
      </li>
    </ul>
  </div>
</nav>
    <router-view/>
    <footer>Copelia Altamirano || CDMX || 2018 </footer>
  </div>
</template>

<style>
.navbar-brand{
  font-family: 'Niramit';
  color: #42b983 !important;
  font-size: 2em;
  padding: 20px;
}
  /* .nav-item{
    font-family: 'Niramit';
    color: #42b983 !important;
    font-size: 1.5em;
  }  */
  /* .router-link-exact-active{
    color: #484B3E;
  } */
  /* .nav-item:hover{
    color: #484B3E;
  } */

  .nav-link{
    font-family: 'Niramit';
    font-size: 1.5em;
  }

  footer{
    font-family: 'Niramit';
    color: #42b983;
    margin-top: 10vw;
    margin-right: 2vw;
    text-align: right;
  }

  @media screen and (max-width: 320px) {
  a{
    font-size: 15px;
  }
  }
</style>
