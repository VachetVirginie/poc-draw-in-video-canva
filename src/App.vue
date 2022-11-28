<template>
  <div id="app">
    <h1>Dessine-moi un mouton</h1>
    <div class="show-area">
      <HelloWorld :outputName="'example'"/>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.show-area {
  width: fit-content;
  margin: 0 auto;
}
</style>
