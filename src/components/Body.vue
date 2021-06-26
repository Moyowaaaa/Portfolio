<template>
    <div class="container">
        <div class="main"><h3>Hi There! I'm</h3>
        <h1>MOYOWA</h1>
        <h4>I'm a Web Developer.</h4>
        <hr></div>
        <br>
        <About />
        <br>
        <br>
        <Gallery />
        <br>
        <Contact />
        <br>
        <footer>
            <p>Copyright &copy; Moyowa 2021</p>
        </footer>
    </div>
</template>

<script>
import About from './About.vue'
import Contact from './Contact.vue'
import Gallery from './Gallery.vue'

export default {
    name: 'Body',
    components: {
        About,
        Contact,
        Gallery
    }
}
</script>

<style scoped>
.container{
    margin-top:50px;;
    width:95%;;
    height:700px;
}
.main{
    margin-top:180px;
    font-family:cursive
}
.main hr{
    width:15.25em
}
.main h3{
    font-size:30px;
    text-align:center;
}
.main h1{
       color:gold;
    font-size:70px;
    text-align:center;
}
.main h4{
    text-align:center;
}
footer{
    margin-top:80px;
    text-align: center;
}

</style>