<script>
import AppLogo from './AppLogo.vue';
export default {
  name : 'AppHeader',
  components: {
    AppLogo
  }
}
</script>

<template>
  <header>
      <div class="container">
          <nav class="navbar navbar-expand justify-content-between p-0">
              <a class="navbar-brand" href="#">
                  <AppLogo class="custom-margin"></AppLogo>
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
</template>



<style>
.custom-margin{
  margin-right:400px;
}
</style>