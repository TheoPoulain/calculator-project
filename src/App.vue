<template>
  <div id="app" class="container">
    <img src="./assets/logo.png" class="logo">
    
    <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator'

export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
.container {
  max-width: 600px;
  margin: 0 auto;
}

.logo {
  display: block;
  margin: 0 auto;
  height: 100px;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
