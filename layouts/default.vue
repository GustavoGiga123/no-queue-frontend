<template>
  <div class="container is-fluid">

    <b-navbar shadow="true">
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://upload.wikimedia.org/wikipedia/commons/6/63/Ibis_Logo_2011.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                Check-In
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/Hospedes' }">
                Hóspedes
            </b-navbar-item>
          <b-navbar-item tag="router-link" :to="{ path: '/dados' }">
                Dados cadastrais
            </b-navbar-item>
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <strong>Voltar para reserva</strong>
                    </a>
                    <a class="button is-light">
                        
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>

    <Nuxt/>

    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Fast Check-In</strong> powered by No Queue. 
          <a target="_blank" href="https://longdogechallenge.com/">FAE Centro Universitário</a>
        </p>
      </div>
    </footer>      
    
  </div>
</template>

