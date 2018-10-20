<template>
  <div id="app">
   <router-view/>
   <ul class="list-unstyled list-inline"> 
      <li><router-link to="/">Go to Home</router-link></li>
      <li><router-link to="/about">Go to About</router-link></li>
      <li><router-link to="/subscriptions">Go to Subscriptions</router-link></li>
      <li><router-link to="/contact">Go to Contact</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
