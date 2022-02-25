<template>
  <div class="home">    
    <img class="foto" src="../assets/foto.jpg" />
    <h1>Aparecida Miranda</h1>
    <h2>Psicóloga Clínica e Esportiva</h2>    
    <h3>CRP 05/42778</h3>
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
  border-width: 5px;
}

h1, h2 {  
  font-family: 'Courier New', Courier, monospace;
}

</style>