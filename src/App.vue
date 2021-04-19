<template>
  <div id="app">   

    <body>
  <main class="container-full">
    <header>
      <h1 style="color: white; border-top: 20px;"> IP Address Tracker </h1>
      <SearchBar/>
      <!-- <RefCard/> -->
    </header>
    <div class="map"></div>
  </main>
</body>
    
    
    
    <Map/>
    <Footer style="text-align: center; position: absolute; bottom: 100px"/>

    
  </div>
</template>





<script>


import SearchBar from './components/SearchBar.vue';
import Map from './components/Map.vue';
//  import RefCard from './components/RefCard.vue'
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    
    SearchBar,
    // RefCard,
    Map,
    Footer
  }
}
</script>
<style lang="scss">
   @import '~bootstrap/scss/bootstrap';
</style>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');


header{
  
  height: 250px;
  margin: 0 auto;
 background-image: url(../images/pattern-bg.png) ;

}
#app {
  font-family: 'Rubik', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>


