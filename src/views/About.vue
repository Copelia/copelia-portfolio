<template>
  <div class="about">
    <div class="container home">
      <div class="row">
        <div class="col-md-6 bio-pic">
          <img class="rounded-circle" src="../assets/cocorali.jpg" alt="copelia descansando">
        </div>
        <div class="col-md-6 bio-info">
          <p class="card-text"> Hola! Soy Copelia Altamirano y soy Front-End Developer.
             Tengo un gusto particular por Vue.js y por las bicicletas. 
             Aquí encontrarás algunos de mis proyectos:</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>

.bio-pic{
  /* text-align: right; */
}

img{
  width: 250px;
  height: 250px;
}

.bio-info{
  margin-top: 7vh;
  font-family: Niramit;
  color: #484B3E;
}

@media (min-width: 740px) { 
  .bio-pic{
    display: inline-block;
  }
  .bio-info{
    display: inline-block;
  }

 }

</style>

