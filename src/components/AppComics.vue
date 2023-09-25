<script>
import comics from '../comics.js';
import AppComicsSon from './AppComicsSon.vue';

export default {

    name: 'AppComics',
    
    components: { AppComicsSon },


    data() {
        return {
            comics
        }
    }
}
</script>

<template>
    <div v-for="comic in comics">

        <AppComicsSon :lnThumb="comic.thumb" :lnPrice="comic.price" :lnSeries="comic.series" :lnType="comic.type" />

    </div>
</template>

<style lang="scss" scoped>
@use '../../src/assets/scss/app.scss' as *;
</style>