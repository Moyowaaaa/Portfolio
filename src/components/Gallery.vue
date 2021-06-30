<template>
    <div class="gallery">
        <h1>Portfolio <hr></h1>
        <div class="works"></div>
    </div>
</template>

<script>
export default {
    name: "Gallery"
}
</script>

<style scoped>
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
    border:2px solid teal;
}
@media screen and (max-width: 600px) {
    .gallery{
        margin-top:550px;
    }
    .works{
        width:auto;
    }
}
</style>