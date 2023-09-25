<script>
import AppLogo from './AppLogo.vue';
export default {
  name: 'AppHeader',
  components: {
    AppLogo
  }
}
</script>

<template>
  <div class="wrapper">
  <header id="site_header">
    <div class="container">
      <nav class="navbar navbar-expand justify-content-between p-0">
        <a class="navbar-brand" href="#">
          <AppLogo></AppLogo>
        </a>

        <div class="nav navbar-nav gx-3">
          <a class="nav-item nav-link" href="#">Characters</a>
          <a class="nav-item nav-link active" href="#">Comics</a>
          <a class="nav-item nav-link" href="#">Movies</a>
          <a class="nav-item nav-link" href="#">Tv</a>
          <a class="nav-item nav-link" href="#">Games</a>
          <a class="nav-item nav-link" href="#">Collectibles</a>
          <a class="nav-item nav-link" href="#">Videos</a>
          <a class="nav-item nav-link" href="#">Fans</a>
          <a class="nav-item nav-link" href="#">News</a>
          <a class="nav-item nav-link" href="#">Shop</a>
        </div>
      </nav>
    </div>
  </header>
</div>
</template>



<style lang="scss" scoped>
@use '../../src/assets/scss/partials/variables' as *;
.wrapper{
  width:100%;
}

#site_header {
  background-color: $dc_white;
  

  a.nav-item {
    text-transform: uppercase;
    font-size: 14px;
    padding: 3rem .5rem;
    color: $dc_dark_light;

    &.active {
      color: $dc_main_blue;
      border-bottom: 4px solid $dc_main_blue;
    }
  }


}
</style>