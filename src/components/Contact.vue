<template>
    <div class="contact">
        <h3>Contact Me Today!!</h3>
        <p>I'm currently open to any Freelance work, send me an Email</P> 
        <p>and i will get back to you as soon as possible.</p>
        <div class="link">
        <a href=""><i class="fa fa-envelope" aria-hidden="true"></i></a>
         <a href=""><i class="fa fa-github" aria-hidden="true"></i></a>
          <a href=""><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                    <a href=""><i class="fa fa-twitter" aria-hidden="true"></i></a>
            </div>
        </div>
</template>

<script>
export default {
    name: 'Contact'
}
</script>

<style>
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

@media screen and (max-width: 600px) {
    .contact{
        margin-top:500px;
    }
}

</style>