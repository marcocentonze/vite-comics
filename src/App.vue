<script>
import AppHeader from './components/AppHeader.vue';
import AppLogo from './components/AppLogo.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppComics from './components/AppComics.vue';
import AppComicsSon from './components/AppComicsSon.vue';



export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppLogo,
    AppComics,
    AppComicsSon,
    AppJumbo,
    AppMain,
    AppFooter,
    
  
}

}
</script>

<template>
  <AppHeader></AppHeader>
  <AppJumbo></AppJumbo>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
 

</template>

<style >

</style>