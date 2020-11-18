<template>
  <div id="app">
    <!--    navbar  -->
    <nav id="nav" class="navbar navbar-expand-lg navbar-dark my-dark mt-3">
      <a class="navbar-brand ml-4 font-weight-bold" href="#">João Ferreira</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav mr-auto">
          <!--    mr-auto para que o próximo vá para a direita.      -->
        </ul>
        <ul class="navbar-nav mr-5">
          <li class="nav-item mr-2">
            <router-link class="nav-link text-white" to="/">
              <p class="d-inline small font-weight-bold text-info mr-2">00. </p>
              Início
            </router-link>
          </li>
          <li class="nav-item mr-2">
            <router-link class="nav-link text-white" to="/about">
              <p class="d-inline small font-weight-bold text-info mr-2">01. </p>
              Sobre mim
            </router-link>
          </li>
          <li class="nav-item mr-2">
            <router-link class="nav-link text-white" to="/about">
              <p class="d-inline small font-weight-bold text-info mr-2">02. </p>
              Experiência
            </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link text-white" to="/about">
              <p class="d-inline small font-weight-bold text-info mr-2">03. </p>
              Tecnologias
            </router-link>
          </li>
        </ul>
      </div>
    </nav>
    <!--  view  -->
    <router-view/>
    <!--  footer-->
    <footer class="page-footer font-small special-color-dark pt-4">

      <!-- Footer Elements -->
      <div class="container">

        <!-- Social buttons -->
        <ul class="list-unstyled list-inline text-center">
          <li class="list-inline-item">
            <a class="btn-floating btn-fb mx-1 facebook-back">
              <i class="fab fa-facebook-f"> </i>
            </a>
          </li>
          <li class="list-inline-item">
            <a class="btn-floating btn-li mx-1 linkedin-back">
              <i class="fab fa-linkedin-in"> </i>
            </a>
          </li>
          <li class="list-inline-item">
            <a class="btn-floating btn-li mx-1 instagram-back">
              <i class="fab fa-instagram"> </i>
            </a>
          </li>
        </ul>
        <!-- Social buttons -->

      </div>
      <!-- Footer Elements -->

      <!-- Copyright -->
      <div class="footer-copyright text-center py-3">© 2020 Copyright:
        <a href="https://www.joaofrf.com/"> www.joaofrf.com</a>
      </div>
      <!-- Copyright -->

    </footer>
    <!-- Footer -->
  </div>
</template>

<style>
    @import './assets/styles/mycss.css';

    .list-inline-item a{
      text-align: center;
      float: left;
      width: 50px;
      height: 50px;
      /*background-color: red;*/
      border-radius: 100%;
      margin-right: 7px; /*space between*/

    }
    .list-inline-item a i{
      font-size: 20px;
      line-height: 50px;
      color: white;
    }

    .facebook-back{
      background-color: #4267B2;
    }

    .linkedin-back{
      background-color: #2867B2;
    }

    .instagram-back{
      background-color: #C13584;
    }


</style>
