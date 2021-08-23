<template>
    <div class="container">
        <div class="main"><h3>Hi There! I'm</h3>
        <h1>MOYOWA</h1>
        <h4>I'm a <b>Web Developer.</b></h4>
        <hr></div>
        <br>
        <div class="ab">
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

            <div class="languages">
                <div id="main">
                   
   <img class="icons"  src="../assets/html.svg" alt="">
   <img class="icon"   src="../assets/css3.svg" alt="">
      <img class="icons"  src="../assets/javascript.svg" alt="">
             <img class="icons" id="ico"  src="../assets/mongodb.svg" alt="">
              <img class="icons" id="ico"  src="../assets/nuxt.svg" alt="">
                <img class="icons" id="ico"  src="../assets/vue-js.svg" alt="">
                <img class="icons" id="ico"  src="../assets/node.svg" alt="">
                </div>
                </div>
           
        </div>

        <br><br>
        <iframe width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=4d52b643-c296-49fb-8b44-46450b9e1451&autoAuth=true&ctid=662847df-c812-48bf-9cee-a61c7c21cec8&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXNvdXRoLWFmcmljYS1ub3J0aC1hLXByaW1hcnktcmVkaXJlY3QuYW5hbHlzaXMud2luZG93cy5uZXQvIn0%3D" frameborder="0" allowFullScreen="true"></iframe>





        <div class="gallery">
        <h1>Portfolio <hr></h1>
        <br><br>
        <div class="works">
          <div class="left">
              <img class="img" src="../assets/project1.jpg">
              <div class="title">
                  <h4>HEDGEHOG</h4>
               
                  <p>A Website for Creating and Tracking Task.</p>
                  <hr>
              </div>
              <div class="lang">
                  <p><l1>Vue.js</l1></p>
              </div>
              <div class="lang">
                  <p>Chakra-ui</p>
              </div>
              <div class="open">
                  <a href="https://xdm-front.vercel.app/">
                  <h3>view</h3></a>
              </div>
          </div>


          <div class="center">
          </div>



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
    width:100%;;
    height:700px;

  
}
.main{
    margin-top:15%;
    height:200%
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
.ab{
    display: flex;
    width:100%;
}
.ab .about{
    width:65%;
    height:auto;
   
}
.about hr{
  width:3.25em;
}

.about p{
    margin-left:15px;
    width:90%;
    margin-bottom: 5%;
    text-align:justify;
    font-size:25px;
}
.ab .languages{
    width:34%; 
}
#main{
    margin-top:25%;
      display: flex;
  flex-wrap: wrap;
}
#main .icon{
    height:65px;
     margin-left:57px;
}

#main .icons{
    margin-left:80px;
    margin-top:10px;
    height: 50px;
}
#main .ico{
    margin-top:5%;
    margin-left:40%;
    height: 50px;
}



/*
#main .tooltiptext{
    visibility:hidden;
    width: 120px;
    background-color:black;
    color:white;
    z-index: 1;
    text-align:center;
     top: 100%;
  left: 50%;
}
#main .tooltiptext::after {
    content: "";
     position: absolute;
     top: 100%;
  left: 50%;

}


#main:hover .tooltiptext {
  visibility: visible;
}
*/


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
    width:90%;
    height:700px;
    margin-left:8%;
    display:flex;
}
.works .left{
  height:60%;
  background:rgb(2, 12, 46);
  width:28%;
}
.works .center{
  height:60%;
  width:28%;
  margin-left:5%;
  background:rgb(2, 12, 46);
}
.works .right{
  height:60%;
  width:28%;
  margin-left:5%;
 background:rgb(2, 12, 46);
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
.left .img{
    width:100%;
    height:40%
}
 .title{
     padding-top:10px;
    margin-top:5%;
    margin-left:5%
}
 .title hr{
    width:5.25em
}

 .lang{
    display:inline-flex;
    border:0.2px solid teal;
    height:25px;
    width:30%;
    margin-left:5%;
 
}
 .open{
  margin-left:5%;
  margin-top:10%;
  width:10%;
  text-decoration:none;
}


.open:hover{
    text-decoration:underline;
}

.open .fa{
    color:white;
    font-size:20px;
}
.open .fa:hover {
    color:gold;
}
 .open h3 {
    color:gold
}
 .open a:hover{
    text-decoration:none;
}
 .open h3:hover {
    text-decoration:none;
}


/* Mobile phones */
@media screen and (max-width: 600px) {
    .contact{
        margin-top:300px;
    }
    .works{
      display: block;;
    }
    .ab{
       display:block
    }  
     .ab .about{
         width:100%;
       display:block
     }
     .ab .languages{
         width:100%;
     }
     #main{   
         display:block;
         flex-direction: row;
         margin-left:6%;
         margin-bottom:10px;

     } 
     #main .icon, #main .icons{
         margin-left:10px;
     }
    .gallery{
        margin-top:300px;
    }
    .works{
      height:auto;
        width:auto;
    }
    .works .left{
      height: 400px;
      width:100%;
      margin-left:-15px;
      margin-top:10px;
      
    }
    .works .center{
         height: 400px;
           margin-left:-15px;
      width:100%;
      margin-top:15px;
    }
    .works .right{
         height: 400px;
      width:100%;
        margin-left:-15px;
      margin-top:15px;
    }
    .about{
        display:block;
    }
    .about .img{
        width:100%;
    }
    .about p{
        width:90%;
    }
    .main{
        margin-top:60%;
    }
    .main h1{
        font-size:65px;
    }
}

</style>
