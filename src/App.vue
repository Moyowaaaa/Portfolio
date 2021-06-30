<template>
<div class="c-container">
  <Nav />
  <br>
  <Body />

</div>
</template>

<script>
import Nav from './components/NavBar.vue'
import Body from './components/Body.vue'

export default {
  components: {
    Nav,
    Body
  }
}
</script>

<style>
body{
  margin:0px;
  background:black; 
  color:white;
}


</style>
