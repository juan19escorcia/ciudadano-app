<template>
  <Projecto/>
</template>

<script>
import Projecto from './components/Projecto.vue'

export default {
  name: 'App',
  components: {
    Projecto
  }
}
</script>

<style>
html{
  height: 100%;
}
body{
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
#app {
  width: 90%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
