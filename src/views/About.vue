<template>
  <div class="about">
    <div class="container home">
      <div class="row">
        <div class="col-md-6 bio-pic">
          <img class="rounded-circle" src="../assets/copelia.jpg" alt="copelia descansando">
        </div>
        <div class="col-md-6 bio-info">
          <p class="card-text"> Hola! Soy Copelia Altamirano, Front-End Developer y psicóloga.
             Tengo un gusto particular por Vue.js, andar en bicicleta y comer postres.
             Ahora mismo estoy en busca de oportunidades laborales. Tengo buena capacidad de análisis, empatía y me gusta trabajar tanto individualmente como en equipos de trabajo.
             Si estás buscando a alguien con una súper habilidad de aprender de forma autónoma, llegaste al lugar correcto.
             </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>

.home{
  margin-top: 10vh;
}

img{
  width: 250px;
  height: 250px;
}

.bio-info{
  margin: auto;
  font-family: Niramit;
  color: #484B3E;
}

.bio-pic{
  margin: auto;
  text-align: center;
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

