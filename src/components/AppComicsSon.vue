<script>
export default {
    name: "AppComicsSon",

    props: {
        lnThumb: String,
        lnPrice: String,
        lnSeries: String,
        lnType: String,
    },


    // funzione per importare immagini dopo build
    methods: {
        getImageUrl(name) {
            return new URL(`${name}`, import.meta.url).href
        }
    } 

   
}
</script>

<template>
    <div class="card mb-3">
    <img :src="getImageUrl(lnThumb)" :alt="lnSeries" class="card-img-top">
    <div class="card-body">
      <h5 class="card-title">{{ lnSeries }}</h5>
      <p class="card-text">Prezzo: {{ lnPrice }}</p>
      <p class="card-text">Tipo: {{ lnType }}</p>
    </div>
  </div>
</template>
  
<style lang="scss" scoped>

</style>