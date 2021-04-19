<template>
  <div class="input-group mb-3">
  <input type="text" class="form-control" placeholder="Search for any IP Address or domain" aria-label="Recipient's username" aria-describedby="button-addon2">
  <button class="btn btn-outline-secondary" type="button" id="button-addon2"> > </button>
</div>
</template>

<script>
export default {
  name: 'SearchBar'
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

.form-control{

  width: 50%;
}

#button-addon2{

  background-color: black;
  color: white
}
</style>


<script type="text/javascript">  
// // Code Sample straight from Geolocation API
// require('dotenv').config();
// import $ from 'jquery';
//  var ip = "8.8.8.8";   

//  $(function () {      
//     $.ajax({url: "https://geo.ipify.org/api/v1",
//     //exposed key, use dotenv
//     data: {apiKey: 'at_k3gOPkHXWEpmSHtqVm6TZF35YnKg6', ipAddress: ip},       
//   success: function(data) {

//       console.log(data);
    
//     }       });    });
  
//   </script>
 
