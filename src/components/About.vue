<template>
    <div>
        <div class="about">
            <div class="img"></div>
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
    </div>
</template>

<script>
export default {
    name:'About'
    
}
</script>

<style scoped>
.about{
    margin-top:300px;
    display: inline-flex;
}
.about .img{
    width:30%;
    height:200px;
    border: 3px solid red;
}
.about p{
    margin-left:15px;
    width:65%;
    height:200px;
    text-align:justify;
    font-size:25px;
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


</style>