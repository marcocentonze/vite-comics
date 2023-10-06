<script>
import comics from '../comics.js';
import AppComicsSon from './AppComicsSon.vue';

export default {
    name: 'AppComics',
    
    components: { AppComicsSon },

    data() {
        return {
            comics,
        }
    }
}
</script>

<template>
    <div class="container">
      <div class="row">
        <div v-for="comic in comics" :key="comic.id" class="col-md-3 p-3">
          <div class="card mb-3 pt-3" style="height: 100%;">
            <img :src="comic.thumb" :alt="comic.series" class="card-img-top">
            <div class="card-body" style="height: 100%;">
              <h5 class="card-title">{{ comic.series }}</h5>
              <p class="card-text">Prezzo: {{ comic.price }}</p>
              <p class="card-text">Tipo: {{ comic.type }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  




<style lang="scss" scoped>
@use '../../src/assets/scss/app.scss' as *;

</style>