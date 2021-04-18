<template>


  <div class="hello">


    <div id = "header" style="position: absolute">
      <h1> IP Address Tracker</h1>
    <img alt="bg" style="position: relative" src="../../images/pattern-bg.png">
      
      </div>

  Search for any IP address or domain

  IP Address
  Location
  Timezone
    UTC <!-- add offset value dynamically using the API -->
  ISP
  
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="https://github.com/Ruok27/IP-Address-Tracker">Jose Fernandez</a>.
  </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }

   
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

 body{width: 100%;
  height: 100%;
  position: absolute; top: 0; left: 0;
  
  
  }
</style>
