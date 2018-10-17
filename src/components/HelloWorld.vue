<template>
  <!-- <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.

    </p>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div> -->
   <div class="container-fluid">
    <div class="row">
      <div class="col-12">
        <h4>{{ profile }}</h4>
        <h5>{{ msg }}</h5>
      </div>
    <div class="row">
      <div class="col-4">
        <div class="card" style="width: 18rem;">
          <div class="card-body-a">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p class="card-text">Proyecto realizado con Vanilla JS, Firebase Authentication, Realtime Database y Bootstrap 4 </p>
            <a href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" class="card-link">Ver proyecto</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card" style="width: 18rem;">
          <div class="card-body-b">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p class="card-text">Proyecto realizado con Vanilla JS, Firebase Authentication, Realtime Database y Bootstrap 4 </p>
            <a href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" class="card-link">Ver proyecto</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card" style="width: 18rem;">
          <div class="card-body-c">
            <h5 class="card-title">Registro de Visitantes</h5>
            <p class="card-text">Proyecto realizado con Vanilla JS, Firebase Authentication, Realtime Database y Bootstrap 4 </p>
            <a href="https://copelia.github.io/core-registro-visitantes/index.html" target="blank" class="card-link">Ver proyecto</a>
          </div>
        </div>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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


// h3
//   margin 40px 0 0

// ul
//   list-style-type none
//   padding 0

// li
//   display inline-block
//   margin 0 10px

// a
//   color #42b983
</style>
