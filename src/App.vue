<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>

<script>
import Header from './components/layout/Header'; 

export default {
   name: "app", 
   components:{
     Header
   }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}

#nav a {
  font-weight: bold;
  color: #666;
}

#nav a.router-link-exact-active {
  color: #fff;
  text-decoration: none;
}
</style>
