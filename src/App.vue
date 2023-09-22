<script>
import AppHeader from './components/AppHeader.vue';
import AppLogo from './components/AppLogo.vue';
import AppMain from './components/AppMain.vue';


export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppLogo,
    AppMain,
  
}

}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
 

</template>

<style >
/* @use './assets/scss/app.scss'; */
</style>