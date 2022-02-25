<template>
  <div id="app">    
    <nav>     
      <router-link to="/">Principal</router-link> 
      <router-link to="/portfolio">Portifólio</router-link> 
      <router-link to="/contact">Contatos</router-link> 
    </nav>
    <router-view />
  </div>
</template>

<script>

export default {
  name: "App"
};
</script>

<style>
body {
  font-family: "PT Sans", sans-serif;
  font-size: 13px;
  font-weight: 400;
  color: #4f5d6e;
  position: relative;  
  background: linear-gradient(to bottom, #8766c4 , #b19cd9);  
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;  
}

nav {
  padding: 30px;
  font-size: x-large;  
  margin-bottom: 50px;
  box-shadow: 5px 4px 5px #000;
  background-color: #b19cd9;  
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  font-size: medium;
  /* box-shadow: 5px 4px 5px #000; */
  padding: 10px;
  margin: 10px;
}

nav a.router-link-exact-active {
  color: #8766c4;
}

</style>
