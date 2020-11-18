<template>
  <div>
    <div class="sobre-mim">
      <h1 class="text-white titulo-about">Sobre mim</h1>
      <p class="text-white descricao-about mt-5">Descobre aqui quem sou, de onde sou e por onde andei</p>
    </div>
    <div class="box">

    </div>
  </div>
</template>

<style>
.sobre-mim{
  height: 200px;
  text-align: center;
}

.titulo-about{
  margin-top: 5%;
  font-size: 350%;
}

.descricao-about{
  font-size: 150%;
}


.box:after {
  height: 70%;
  content: ' ';
  border-top: 10vh solid #191a1d;
  border-left: 100vw solid white;
  position: absolute;
}
</style>
