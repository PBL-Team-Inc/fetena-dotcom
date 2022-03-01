<template>
  <navbar/>
</template>
<script>

import navbar from './components/NavBar/Navbar.vue'

export default{
  components: {
    navbar
  }
  
}
</script>

<style>
#app {
  background: url('./assets/BG.jpg') no-repeat; 
  background-size: cover;
  height: 100%;
  width: 100%;
  margin: 0;
  position: absolute;
  top: 0;
  left: 0;
  
}


</style>
