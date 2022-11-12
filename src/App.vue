<template>
  <div id="app">
    <CalculatorView></CalculatorView>
  </div>
</template>

<script>
  import CalculatorView from "./components/Calculator.vue";
  export default {
    name: "App",
    components: {
      CalculatorView,
    },
  };
</script>

<style>
  body {
    background: #31475e !important;
  }
</style>
