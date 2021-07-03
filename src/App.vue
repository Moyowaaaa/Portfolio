<template>
<div id="app">
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
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/about">About</router-link></li>
            <li><router-link to="/Contact">Contact Me</router-link></li>
            <li><a href="https://www.linkedin.com/in/moyowa-etchie-665b51189"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
            <li><a href="https://github.com/Pope-Skittles"><i class="fa fa-github" aria-hidden="true"></i></a></li>
            
              </ul>
        </div>
      </div>
    </div>
  </nav> 
  </body>  

  <router-view/> 
</div>
</template>



<style>
body{
  background-color:black !important;
    color:white !important;
}


.navbar-brand {
    margin:5px;
    
    font-size:15px;

}
.navbar-nav{
    float:right;

}


.navbar-nav .fa{
    color:teal;;
    font-size:20px
}
.navbar-nav .fa:hover{
  color:black;
  background:gold;
  margin-left:2px;
  text-align:center;
  width:50px;
}

@media screen and (max-width: 600px) {
    .main{
        margin-top:150px;
    }
    .main h1{
        font-size:65px;
    }
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
