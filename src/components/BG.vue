<template>

<div class="BG">


    <div id = "header" style="position: absolute">
      <h1 style="weight: 400"> IP Address Tracker</h1>
  
     
      </div>
  </div>

  
</template>

<script>
export default {
  name: 'BG',
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

 .BG{width: 100%;
  height: 100%;
  position: absolute; top: 0; left: 0;
  background-image: url(../../images/pattern-bg.png) 
  
  }
</style>
