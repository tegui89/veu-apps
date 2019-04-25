<template>
  <div id="app">
    <Headers/>
    <MenuNav/>
    <Slider/>
  </div>
</template>

<script>
import Headers from './components/Headers.vue'
import MenuNav from './components/MenuNav.vue'
import Slider from './components/Slider.vue'

export default {
  name: 'app',
  components:{
    Headers,
    MenuNav,
    Slider
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
  margin-top: 0px;
}
</style>
