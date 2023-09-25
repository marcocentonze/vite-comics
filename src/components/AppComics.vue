<script>
import comics from '../comics.js';

export default {

    name: 'AppComics',

    data() {
        return {
            comics
        }
    }
}
</script>

<template>
    <div v-for="comic in comics">

        <div>{{ comic.series }}</div>

    </div>
</template>

<style lang="scss" scoped>
@use '../../src/assets/scss/app.scss' as *;
</style>