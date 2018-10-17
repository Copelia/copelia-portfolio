<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <Hello msg="Front-end Developer" profile="Copelia Altamirano"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Hello from '@/components/Hello.vue';

export default {
  name: 'home',
  components: {
    Hello,
  },
};
</script>
