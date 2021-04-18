

<template>
  <div id="app">
   
    
    <HelloWorld/>
    <SearchBar/>
  </div>
</template>





<script>

import HelloWorld from './components/HelloWorld.vue';
import SearchBar from './components/SearchBar.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
    SearchBar
  }
}
</script>
<style lang="scss">
   @import '~bootstrap/scss/bootstrap';
</style>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');



#app {
  font-family: 'Rubik', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}
</style>
