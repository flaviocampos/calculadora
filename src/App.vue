<template>

  <div id="app">
    <h1>Calculadora</h1>
    <Calculator />
  </div>

</template>

<script>
import Calculator from './main/Calculator.vue';
export default {
  components: { Calculator }
}
</script>

<style>
@font-face {
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
  font-family: "RobotoMono", monospace;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color: #fff;
  background: rgb(2, 0, 36);
  background: linear-gradient(90deg, rgba(2, 0, 36, 1) 0%, rgba(9, 9, 121, 1) 71%, rgba(0, 212, 255, 1) 100%);
}
</style>
