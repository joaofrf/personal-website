<template>
  <div id="app">
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
    <router-view/>
  </div>
</template>

<style>
    @import './assets/styles/mycss.css';
</style>
