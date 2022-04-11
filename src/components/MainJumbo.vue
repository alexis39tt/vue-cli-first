<template>
  <div>
    <div class="img">
      <img src="https://i.picsum.photos/id/3/1920/500.jpg?hmac=AZjoCQ6sUGgl53p3ag0NQiwAHrKBNchj1h_ox9cfB5o">
    
    <div class="text">
      <h2>Questo è un jumbotron</h2>
      <p>E contiene un'immagine e del testo</p>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainJumbo',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.img{
  display: flex;
  position: relative;
}
img{
  width: 100%;
  margin: 0 auto 50px;
}
.text{
  position: absolute;
  bottom: 20%;
  left: 2%;
  color: white;
  font-size: 2rem;
  text-shadow: 3px 3px 3px black;
}
</style>
