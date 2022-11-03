<template>
  
  <projecto/>
</template>

<script>
import Projecto from './components/projecto.vue'

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
  justify-content: center; 
  align-items: center;
}
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 100%;
}
</style>
