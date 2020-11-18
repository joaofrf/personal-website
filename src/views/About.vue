<template>
  <div>
    <div class="sobre-mim">
      <h1 class="text-white titulo-about">Sobre mim</h1>
      <p class="text-white descricao-about mt-5">Descobre aqui quem sou, de onde sou e por onde andei</p>
    </div>

    <div class="box">
    </div>
    <div class="sobre-mim-info pt-5">
      <div class="who-am-i">
        <h1>Quem sou?</h1>
        <p>O meu nome é João Ferreira, tenho 22 anos e sou um programador atualmente a viver em leiria.</p>
      </div>
    </div>

  </div>
</template>

<style>
.sobre-mim{
  height: 200px;
  text-align: center;
}

.titulo-about{
  font-weight: bold;
  margin-top: 5%;
  font-size: 350%;
}

.descricao-about{
  font-size: 150%;
}


.box {
  height: 10%;
  content: ' ';
  border-top: 10vh solid #191a1d;
  border-left: 100vw solid white;
}

.sobre-mim-info{
  height: 750px;
  background-color: white;
}

.who-am-i{
  display: table;
  margin: 0 auto;
}

</style>
