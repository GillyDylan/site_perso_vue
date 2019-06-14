<template>
  <div id="site">
    <Background />
    <div class="corp">
      <div class="row align-items-center no-gutters justify-content-md-center corp-haut">
        <div class="col-1 col-sm-2 col-xl-3 poignee">
          <div class = "bougie">
            <picture>
              <source media="(min-width: 651px)"  srcset= "./assets/img/flamme.png">
              <source media="(max-width: 650px)"  srcset= "./assets/img/flamme-mini.png">
              <img class = "bougie-flamme" src="./assets/img/flamme.png">
            </picture>
            <picture>
              <source media="(min-width: 651px)" srcset= "./assets/img/mur.png">
              <source media="(max-width: 650px)" srcset= "./assets/img/mur-mini.png">
              <img class = "bougie-mur" src="./assets/img/mur.png">
            </picture>

          </div>
        </div>
        <div class="col-10 col-sm-8 col-xl-6 ombre animation" id="barre">
          <div class="row align-items-center no-gutters justify-content-md-center menu barre" >
            <div class="col-4 text-center laterals boutton boutton-menu animation" id="Accueil"  name="boutton-menu" >
              <div>
                <label>Accueil</label>
              </div>
            </div>
            <div class="col-4 text-center laterals boutton boutton-menu animation" id="Competences"  name="boutton-menu">
              <div>
                <label>Compétences</label>
              </div>
            </div>
            <div class="col-4 text-center laterals boutton boutton-menu animation" id="Travaux"  name="boutton-menu">
              <div>
                <label>Travaux</label>
              </div>
            </div>
          </div>
        </div>
        <div class="col-1 col-sm-2 col-xl-3 poignee inverse" >
          <div class = "bougie">
            <picture>
              <source media="(min-width: 651px)"  srcset="./assets/img/flamme.png">
              <source media="(max-width: 650px)"  srcset="./assets/img/flamme-mini.png">
              <img class = "bougie-flamme" src="./assets/img/flamme.png">
            </picture>
            <picture>
              <source media="(min-width: 651px)" srcset="./assets/img/mur.png">
              <source media="(max-width: 650px)" srcset="./assets/img/mur-mini.png">
              <img class = "bougie-mur" src="./assets/img/mur.png">
            </picture>
          </div>
        </div>
      </div >
      <div class="corp-contenu">
        <div class="row align-items-center no-gutters justify-content-md-center contenu animation" id="contenu">
          <div class="row align-items-center no-gutters justify-content-md-center contenu-haut">
            <div class="col-1 col-sm-2 col-xl-3">
            </div>
            <div class="col-10 col-sm-8 col-xl-6 page" id="page">
              <div id="contenu-page" >

              </div>
            </div>
            <div class="col-1 col-sm-2 col-xl-3 ">
            </div>
          </div>
          <div class="row align-items-center no-gutters justify-content-md-center contenu-bas">
            <div class="col-1 col-sm-2 col-xl-3 poignee-bas">
            </div>
            <div class="col-10 col-sm-8 col-xl-6 bas-de-page">
            </div>
            <div class="col-1 col-sm-2 col-xl-3 poignee-bas inverse">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Background from './components/Background.vue'

export default {
  name: 'app',
  components: {
    Background
  }
}
</script>

<style>
  @import 'assets/css/style.css';
  @import 'assets/css/vendor/bootstrap.min.css';
  @import 'assets/css/vendor/bootstrap-grid.min.css';
</style>
