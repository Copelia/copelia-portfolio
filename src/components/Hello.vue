<template>
   <div class="container-fluid">
    <div class="row">
      <div class="col-12">
        <h4>{{ profile }}</h4>
        <h5>{{ msg }}</h5>
      </div>
    <div class="row">
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <div class="card-body-a">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p class="card-text">Proyecto realizado con Vanilla JS, Firebase Authentication, Realtime Database y Bootstrap 4 </p>
            <a href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" rel="noopener">Ver proyecto</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4 col-12">
        <div class="card" style="width: 18rem;">
          <div class="card-body-b">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p><i class="fab fa-js"></i></p>
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
  </div>
</template>

<script>
export default {
  name: 'Hello',
  props: {
    msg: String,
    profile: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
   .card-body-a {
     background-color: #969696;
   }
    .card-body-b {
     background-color: #00bcd4;
   }
    .card-body-c {
     background-color: #ff80ab;
   }
</style>
