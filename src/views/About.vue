<template>
  <div class="d-flex justify-content-center mt-5">
    <!-- source https://stackoverflow.com/questions/45666656/bootstrap-4-responsive-utilities-visible-hidden-xs-sm-lg-not-working -->
    <!--	Computer	-->
    <div class="row d-none d-lg-flex d-xl-none d-xl-flex">
      <div class="col-xs-6 text-center">
        <img src="https://aerp.pt/portal/wp-content/uploads/2015/07/img_raul.jpg" width="430px" class="photo" alt="Foto da minha escola no ensino secundário">
      </div>
      <div class="col-xs-6 text-center text-justify text-white ml-5">
        <p class="text-left m-auto">Comecei a programar na </p>
        <h3 class="d-flex">Escola Secundária Raul Proença</h3>
        <p class="text-left mt-2">Onde frequentei o curso profissional PTGPSI</p>
      </div>
    </div>
    <div class="row d-none d-lg-flex d-xl-none d-xl-flex">
      <div class="col-xs-6 text-center text-justify text-white ml-5">
        <p class="text-left m-auto">Comecei a programar na </p>
        <h3 class="d-flex">Escola Secundária Raul Proença</h3>
        <p class="text-left mt-2">Onde frequentei o curso profissional PTGPSI</p>
      </div>
      <div class="col-xs-6 text-center">
        <img src="https://aerp.pt/portal/wp-content/uploads/2015/07/img_raul.jpg" width="430px" class="photo" alt="Foto da minha escola no ensino secundário">
      </div>
    </div>
    <!--	Mobile    -->
    <div class="row d-block d-sm-block d-md-block d-lg-none m-auto">
      <div class="col-xs-6 text-center">
        <img src="https://aerp.pt/portal/wp-content/uploads/2015/07/img_raul.jpg" class="photo" alt="Uma foto minha">
      </div>
      <div class="col-xs-6 text-center text-white mt-5">
        <p class="m-auto">Comecei a programar na </p>
        <h3 class="d-flex">Escola Secundária Raul Proença</h3>
        <p class="m-auto">Onde frequentei o curso profissional PTGPSI</p>
      </div>
    </div>
  </div>
</template>
