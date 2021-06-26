<template>
<div>
     <body data-spy="scroll" data-target=".navbar" data-offset="50">

  <nav class="navbar navbar-inverse navbar-fixed-top">
    <div class="container-fluid">
      <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>                        
        </button>
        <h3 class="navbar-brand" >Moyowa Etchie</h3>
      </div>
      <div>
        <div class="collapse navbar-collapse" id="myNavbar">
          <ul class="nav navbar-nav">
            <li><a href="#section2">About Me</a></li>
            <li><a href="#section3">Services</a></li>
            <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
            <li><a href="#"><i class="fa fa-github" aria-hidden="true"></i></a></li>
            
              </ul>
        </div>
      </div>
    </div>
  </nav> 
  </body>   
  </div>
</template>

<script>
export default {
    name: 'Nav'
}
</script>

<style scoped>
.navbar{
    background: black;;
    height:auto;
    }
  
.navbar a{
    text-decoration: none;;
    color:teal;;
}
.navbar-brand {
    margin:5px;
    font-family:cursive;
    font-size:25px;

}
.navbar-nav{
    float:right;
    font-family:cursive;
}
.nav li{
  color:red;
}
.navbar-nav .fa{
    color:steelblue;
    font-size:20px
}
.navbar-nav .fa:hover{
  color:gold;
  margin-left:20px;
}
@media screen and (max-width: 600px) {
    .navbar-nav{
    float:none;;
    }
}
@media screen and (max-width: 900px) {
    .navbar-nav{
    float:none;;
    }
}
</style>
