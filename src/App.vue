<template>
  <div id="app">
    <div class="nav">
      <router-link to="/">Inicio  |</router-link>
      <router-link to="/about">  ¿Quién?  |</router-link>
      <router-link to="/contact">  ¿Dónde?</router-link>
    </div>
    <div class="header">
      <h4>Copelia Altamirano</h4>
      <h5>Front-end Developer</h5>
    </div>
    <router-view/>
  </div>
</template>

<style>
.nav{
  font-family: 'Cabin Sketch';
  text-align: right;
  color: #42b983;
  padding: 30px;
}
  a{
    font-weight: bold;
    color: #42b983;
    font-size: 3vw;
  }
  .router-link-exact-active{
    color: #484B3E;
  }
  a:hover{
    color: #484B3E;
  }

 .header{
     text-align: right;
     margin-bottom: 0.5em;
     font-size: 2vw;
     color: #484B3E;
  }

  @media screen and (max-width: 375px) {
  a{
    font-size: 20px;
  }

  .header{
    font-size: 15px;
  }
}
</style>
