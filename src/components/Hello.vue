<template>
   <div class="container-fluid">
    <div class="row">
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <div class="card-body-a">
          <img class="card-img-top" src="../assets/registro.png" alt="Card image cap" style="width: 286px; height: 180px;">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p class="card-text">Proyecto para mejorar el proceso de registro de visitantes en un coworking.</p>
            <a class="view-gh" href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" rel="noopener">Ver proyecto</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" src="../assets/GarnachApp.jpg" alt="Card image cap" style="width: 286px; height: 180px;">
          <div class="card-body-b">
            <h5 class="card-title">Garnachapp</h5>
            <p class="card-text">Red social para compartir alimentos típicos mexicanos.</p>
            <a class="view-gh" href="https://github.com/Copelia/cdmx-2018-06-bc-core-am-social-network" target="blank" rel="noopener">Ver proyecto</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="../assets/foodmap.png" alt="Card image cap" style="width: 286px; height: 180px;">
          <div class="card-body-a">
            <h5 class="card-title">Food Map</h5>
            <p class="card-text">Proyecto para localizar locales de comida de acuerdo a tu ubicación.</p>
            <a class="view-gh" href="https://github.com/Copelia/food-map" target="blank" rel="noopener">Ver proyecto</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <h2>Herramientas</h2>
        <ul>
          <li>Vue.js</li>
          <li>Firebase</li>
          <li>Git</li>
          <li>Bootstrap</li>
          <li>Node.js</li>
        </ul>


      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped lang="stylus">
   .card{
    /* top | right | bottom | left */
    margin: 5vw 2vw 5vw 2vw;
   }
   h5 {
    font-family: Niramit;
    color: #484B3E;
    text-align: center;
    font-size: 20px;
    margin-top:10px;
   }
    .card-body-a {
     background-color: #C3D1C4;
   }
    .card-body-b {
     background-color: #E6E2C6;
   }
   p{
     text-align: center;
   }
   .view-gh{
    text-align: right !important;
    font-family: Niramit;
    color: #419B7F;
    font-weight: 500;
   }
   h2{
    font-family: Niramit;
    color: #484B3E;
    margin-left: 8vh;
    text-align: center;

   }


</style>
