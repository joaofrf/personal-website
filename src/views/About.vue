<template>
  <div>
    <div class="disgrid justify-content-center">
      <!-- source https://stackoverflow.com/questions/45666656/bootstrap-4-responsive-utilities-visible-hidden-xs-sm-lg-not-working -->
      <!--	Computer	-->
      <!--  row 1  -->
      <div class="row d-none d-lg-flex d-xl-none d-xl-flex mt-5">
        <div class="col-xs-6 text-center">
          <img src="https://aerp.pt/portal/wp-content/uploads/2015/07/img_raul.jpg" width="430px" class="photo" alt="Foto da minha escola no ensino secundário">
        </div>
        <div class="col-xs-6 text-center text-justify text-white ml-5">
          <p class="text-left m-auto">Comecei a programar na </p>
          <h3 class="d-flex">Escola Secundária Raul Proença</h3>
          <p class="text-left mt-2">Onde frequentei o curso profissional PTGPSI 2015-2017</p>
        </div>
      </div>
      <!--  row 2  -->
      <div class="row d-none d-lg-flex d-xl-none d-xl-flex mt-5">
        <div class="col-xs-6 text-center text-justify text-white">
          <p class="text-left m-auto">Ganhei cada vez mais gosto pela área e decidi ingressar na </p>
          <h3 class="">ESTG Leiria</h3>
          <p class="text-left mt-2">Onde me licenciei em Engenharia Informática 2017 - 2021</p>
        </div>
        <div class="col-xs-6 text-center ml-5">
          <img src="https://scontent.flis4-1.fna.fbcdn.net/v/t1.0-9/84751568_10157732597421855_7764067893431500800_n.jpg?_nc_cat=102&ccb=3&_nc_sid=730e14&_nc_ohc=sQ_HPnYTZzQAX_ek7-E&_nc_ht=scontent.flis4-1.fna&oh=bb829e3344aa1522cbbed0d3f043e9c0&oe=6051AA15" width="430px" class="photo" alt="Foto da minha escola no ensino secundário">
        </div>
      </div>
    </div>
    <!--	Mobile    -->
    <!--  row 1  -->
    <div class="justify-content-center mt-3">
      <div class="row d-block d-sm-block d-md-block d-lg-none m-auto">
        <div class="col-xs-6 text-center">
          <img src="https://aerp.pt/portal/wp-content/uploads/2015/07/img_raul.jpg" class="photo" alt="Uma foto minha">
        </div>
        <div class="col-xs-6 text-center text-white mt-2">
          <p class="m-auto">Comecei a programar na </p>
          <h3 class="">Escola Secundária Raul Proença</h3>
          <p class="m-auto">Onde frequentei o curso profissional PTGPSI 2015-2017</p>
        </div>
      </div>
      <!--  row 2  -->
      <div class="row d-block d-sm-block d-md-block d-lg-none m-auto pt-5">
        <div class="col-xs-6 text-center">
          <img src="https://scontent.flis4-1.fna.fbcdn.net/v/t1.0-9/84751568_10157732597421855_7764067893431500800_n.jpg?_nc_cat=102&ccb=3&_nc_sid=730e14&_nc_ohc=sQ_HPnYTZzQAX_ek7-E&_nc_ht=scontent.flis4-1.fna&oh=bb829e3344aa1522cbbed0d3f043e9c0&oe=6051AA15" width="430px" class="photo" alt="Foto da minha escola no ensino secundário">
        </div>
        <div class="col-xs-6 text-center text-white mt-2">
          <p class="m-auto">Ganhei cada vez mais gosto pela área e decidi ingressar na </p>
          <h3 class="">ESTG Leiria</h3>
          <p class="m-auto">Onde me licenciei em Engenharia Informática 2017 - 2021</p>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'About',
  components: {
    // HelloWorld
  }
}
</script>

<style>

.disgrid{
  display: grid;
}

</style>