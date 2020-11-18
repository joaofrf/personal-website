<template>
  <div class="centerPseudo">
    <div class="info">
      <h1 class="text-white apresentacao ml-5">Olá, sou o João.</h1>
      <p class="myinfo">Sou um developer, natural das Caldas da Rainha.</p>
<!--      <p class="myinfo">A minha área de maior interesse neste momento é web mas gosto de tudo um pouco!</p>-->
    </div>
    <img class="photo" src="/imgs/eu.jpg" alt="Uma foto minha">
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  }
}
</script>

<style>

.centerPseudo {
  width: 60%;
  height: 60%;
  position: absolute;
  top:0;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
}

.info {
  width: 60%;
  float: left;
}

.photo {
  width: 35%;
  float: left;
  margin-left: 5%;
  background: black;
}

.apresentacao{
  text-align: left;
  font-size: 350%;
}

.myinfo{
  margin-top: 5%;
  text-align: left;
  font-size: 150%;
  color: lightgray;
}


</style>
