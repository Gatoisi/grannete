<template>
  <div>
    <div>
      <test/>
      <test2/>
      <test3/>
    </div>
  </div>
</template>

<script>
import test from './components/test.vue';
import test2 from './components/test2.vue';
import test3 from './components/test3.vue';

export default {

  name: 'App',
  components: {
    test,
    test2,
    test3
  }
}
</script>

<style>

  .header {
  width: 100%;
  min-width: 100vh;
  background-image: url(assets/fondo.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
}
 
</style>
