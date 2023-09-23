<script>
import AppHeader from './components/AppHeader.vue';
import AppLogo from './components/AppLogo.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';


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
    AppFooter,
  
}

}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
 

</template>

<style >
/* @use './assets/scss/app.scss'; */
</style>