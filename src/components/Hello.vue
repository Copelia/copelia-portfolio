<template>
   <div class="container-fluid">
      <div class="header">
        <h4>Copelia Altamirano</h4>
        <h5>Front-end Developer</h5>
      </div>
    <div class="row">
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <div class="card-body-a">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p><i class="fab fa-js"></i></p>
            <p class="card-text">Proyecto realizado con Vanilla JS, Firebase Authentication, Realtime Database y Bootstrap 4 </p>
            <a href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" rel="noopener">Ver proyecto</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <div class="card-body-b">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p class="card-text">Proyecto realizado con Vanilla JS, Firebase Authentication, Realtime Database y Bootstrap 4 </p>
            <a href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" rel="noopener">Ver proyecto</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <div class="card-body-c">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p><i class="fab fa-vuejs"></i></p>
            <p class="card-text">Proyecto realizado con Vanilla JS, Firebase Authentication, Realtime Database y Bootstrap 4 </p>
            <a href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" rel="noopener">Ver proyecto</a>
          </div>
        </div>
      </div>
    </div>
    </div>
</template>

<script>
export default {
  name: 'Hello',
  props: {
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
   h4,
   h5 {
    font-family: Niramit;
   }

   .header{
     text-align: right;
     margin-bottom: 0.5em;
     font-size: 4em;
     color: #373D3F;
   }
   .card-body-a {
     background-color: #419B7F;
   }
    .card-body-b {
     background-color: #F2D7E0;
   }
    .card-body-c {
     background-color: #F9D3B4;
   }
</style>
