<template>
   <div class="container-fluid">
    <div class="row">
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <div class="card-body-a">
          <img class="card-img-top" src="../assets/registro.png" alt="Card image cap" style="width: 286px; height: 180px;">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p class="card-text">Proyecto para mejorar el proceso de registro de visitantes en un coworking.</p>
            <div class="row">
            <div class="col-6">
            <a class="view-gh" href="https://github.com/Copelia/core-registro-visitantes" target="blank" rel="noopener">Ver código</a>
            </div>
            <div>
            <a class="view-gh" href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" rel="noopener">Ver proyecto</a>
            </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" src="../assets/GarnachApp.jpg" alt="Card image cap" style="width: 286px; height: 180px;">
          <div class="card-body-b">
            <h5 class="card-title">Garnachapp</h5>
            <p class="card-text">Red social para compartir alimentos típicos mexicanos.</p>
            <div class="row">
            <div class="col-6">
            <a class="view-gh" href="https://github.com/Copelia/cdmx-2018-06-bc-core-am-social-network" target="blank" rel="noopener">Ver código</a>
            </div>
            <div class="col-6">            
            <a class="view-gh" href="https://jetzable.github.io/cdmx-2018-06-bc-core-am-social-network/src/" target="blank" rel="noopener">Ver proyecto</a>
            </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="../assets/labcar.png" alt="Card image cap" style="width: 286px; height: 180px;">
          <div class="card-body-a">
            <h5 class="card-title">LabCar</h5>
            <p class="card-text">Proyecto de maquetación para una empresa de transporte.</p>
            <div class="row">
            <div class="col-6">
            <a class="view-gh" href="https://github.com/Copelia/labcar-proyecto-maquetacion" target="blank" rel="noopener">Ver código</a>
            </div>
            <div class="col-6">
            <a class="view-gh" href="https://copelia.github.io/labcar-proyecto-maquetacion/src/index.html" target="blank" rel="noopener" style="text-align: right;">Ver proyecto</a>
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row justify-center">
      <div class="col-12">
        <h2>Herramientas</h2>
        <div class="stack-list">
          <i class="devicon-bootstrap-plain colored"></i>
          <i class="devicon-vuejs-plain colored"></i>
          <i class="devicon-git-plain colored"></i>
          <i class="devicon-nodejs-plain colored"></i>
          <!-- <i class="devicon-mongodb-plain colored"></i> -->
          <i class="devicon-sass-original colored"></i>
         </div>
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
    margin-left: 2vw;
    text-align: center;
   }
   i{
    font-size: 4em;
    // margin: 1em 1em 1em 0.5em;
    margin: 5vw 2vw 5vw 2vw;
   }
   .stack-list{
    margin-top: 3vw;
    text-align: center;
   }

   @media screen and (max-width: 375px) {
  i{
    font-size: 2em;
    margin: 5vw 2vw 5vw 2vw;
  }
}


</style>
