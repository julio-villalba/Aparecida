<template>
  <div class="home">    
    <img class="foto" src="../assets/foto.jpg" />
    <h1>Aparecida Miranda</h1>
    <h2>Psicóloga</h2>    
  </div>
</template>

<script>

export default {
  name: "HomeView"
};
</script>

<style>
.foto {
  height: 25%;
  width: 25%;
  border-radius: 50%;
  border-style: solid; 
  border-width: 8px;
}

h1, h2 {  
  font-family: 'Courier New', Courier, monospace;
}

</style>