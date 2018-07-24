<template>
  <div id="app">
    <Weather></Weather>
  </div>
</template>

<script>
import Weather from './components/Weather.vue'

export default {
  name: 'app',
  components:{
      'Weather' : Weather
  }
}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
 width: 100vw;
 height: 100vh;
 display: flex;
 align-items: center;
 justify-content: space-around;
}
</style>