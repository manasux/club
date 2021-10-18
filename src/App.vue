<template>
  <div class="app">
    <Compiler/>
  </div>
</template>

<script>
import Compiler from './components/Compiler.vue'

export default {
  name: 'App',
  components: {
    Compiler,
  }
}
</script>

<style>
@import "./base.css";

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.app {
  width: 100vw;
  height: 100vh;
  /* background-color: red; */
}

</style>
