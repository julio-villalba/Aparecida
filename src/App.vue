<template>
  <div id="app">    
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/portfolio">Portfolio</router-link> |
      <router-link to="/contact">Contact</router-link>
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
  background: linear-gradient(to right, #8766c4 , #b19cd9);  
  filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#1a315f', endColorstr='#1a315f', GradientType=0);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;  
}

.body-wrap {
  min-height: 700px;
}

.body-wrap {
  position: relative;
  z-index: 0;
}

.body-wrap:before,
.body-wrap:after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  z-index: -1;
  height: 260px;
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(26, 49, 95, 1)),
    color-stop(100%, rgba(26, 49, 95, 0))
  );
  background: linear-gradient(
    to bottom,
    rgba(26, 49, 95, 1) 0%,
    rgba(26, 49, 95, 0) 100%
  );
  filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#1a315f', endColorstr='#001a315f', GradientType=0);
}

.body-wrap:after {
  top: auto;
  bottom: 0;
  background: linear-gradient(
    to bottom,
    rgba(26, 49, 95, 0) 0%,
    rgba(26, 49, 95, 1) 100%
  );
  filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#001a315f', endColorstr='#1a315f', GradientType=0);
}

nav {
  padding: 30px;
  font-size: xx-large;  
  margin-bottom: 50px;
  box-shadow: 5px 4px 5px #000;
  background-color: #b19cd9;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #8766c4;
}
</style>
