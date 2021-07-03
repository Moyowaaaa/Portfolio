<template>
    <div class="container">
        <div class="main"><h3>Hi There! I'm</h3>
        <h1>MOYOWA</h1>
        <h4>I'm a <b>Web Developer.</b></h4>
        <hr></div>
        <br>
       <div class="about">
         <h2>About Me<hr></h2>
            <br />
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                consectetur adipisicing elit. In, 
                eaque iure fugit omnis odio quo reprehenderit
                ? Unde commodi, at
                fugit omnis odio quo reprehenderit? Unde commodi, 
                at dolores accusamus itaque quae aspernatur 
                adipisci eaque molestiae enim atque perferendis.
                 dolores accusamus itaque quae aspernatur adipisci e
            aque molestiae enim atque perferendis.</p>
        </div>
        <div class="gallery">
        <h1>Portfolio <hr></h1>
        <br><br>
        <div class="works">
          <div class="left"></div>
          <div class="center"></div>
          <div class="right"></div>
        </div>
        <br>
         <div class="contact">
        <h3>Contact Me Today!!</h3>
        <p>I'm currently open to any Freelance work, send me an Email</P> 
        <p>and i will get back to you as soon as possible.</p>
        <div class="link">
        <a href="mailto:moyowa7@icloud.com"><i class="fa fa-envelope" aria-hidden="true"></i></a>
         <a href="https://github.com/Pope-Skittles"><i class="fa fa-github" aria-hidden="true"></i></a>
          <a href="https://www.linkedin.com/in/moyowa-etchie-665b51189"><i class="fa fa-linkedin"></i></a>
                    <a href="https://twitter.com/Etchie____"><i class="fa fa-twitter" aria-hidden="true"></i></a>
            </div>
        </div>
    </div>
        <br>
        <footer>
            <p>Copyright &copy; Moyowa 2021</p>
        </footer>
    </div>
</template>


<script>
export default {
  name: 'Home',
  components: {

  }
}
</script>


<style>

.container{
    margin-top:50px;;
    background-color:black !important;
    color:white !important;
    width:95%;;
    height:700px;

  
}
.main{
    margin-top:180px;
    
  
}
.main hr{
    width:15.25em
}
.main h3{
    font-size:20px;
    text-align:center;
}
.main h1{
       color:gold;
    font-size:100px;
    text-align:center;
     font-family: Schoolbell;
}
.main h4{
    text-align:center;
}
.about{
  text-align:center;
}
footer{
    margin-top:100%;;
    text-align: center;
}
.about{
    margin-top:300px;
  
}
.about hr{
  width:3.25em;
}

.about p{
    margin-left:15px;
    width:65%;
    height:200px;
    text-align:justify;
    font-size:25px;
}
.gallery{
    margin-top:200px;
}
.gallery h1{
    text-align:center;
}
.gallery hr{
    width:3.25em;
}
.works{
    width:100%;
    height:700px;
  
    display:inline-flex;
}
.works .left{
  height:350px;
  border: 3px solid red;
  width:30%;
}
.works .center{
  height:350px;
  width:30%;
  margin-left:5%;
  border: 3px solid whitesmoke;
}
.works .right{
  height:350px;
  width:30%;
  margin-left:5%;
  border: 3px solid blue;
}


.contact{
    margin-top:350px;
    
}
.contact h3{
    text-align:center;
    font-size:45px;
    
}
.contact p{
    text-align:center;

    font-size:25px;
}
.link{
    text-align:center;
    
    margin-top:80px;
}
.link a{
    margin-left:40px;
    color:teal;
    font-size:35px;
}
.link a:hover{
    color:gold;
}
footer{
    margin-top:80px;
    text-align: center;
}

@media screen and (max-width: 600px) {
    .contact{
        margin-top:500px;
    }
    .works{
      display: block;;
    }
}

@media screen and (max-width: 600px) {
    .gallery{
        margin-top:550px;
    }
    .works{
      height:auto;
        width:auto;
    }
    .works .left{
      height: 350px;
      width:100%;
      margin-left:0px;
      margin-top:10px;
      
    }
    .works .center{
      width:100%;
      margin-left:0px;
      margin-top:10px;
    }
    .works .right{
      width:100%;
      margin-left:0px;
      margin-top:10px;
    }
}
@media screen and (max-width: 600px) {
    .about{
        display:block;
    }
    .about .img{
        width:100%;
    }
    .about p{
        width:90%;
    }
}

@media screen and (max-width: 600px) {
    .main{
        margin-top:150px;
    }
    .main h1{
        font-size:65px;
    }
}

</style>
