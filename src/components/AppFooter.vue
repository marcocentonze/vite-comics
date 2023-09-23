<script>
import AppLogo from './AppFooter.vue';
export default {
    name: 'AppFooter',
    components: {

    }
}
</script>

<template>
    <footer id="site_footer">
        <!-- Top Part -->
        <section class="container d-flex custom-bg-img">

            <!-- 1 div -->
            <div class="d-flex custom-width flex-column justify-content-start pt-4 me-3">
                <h5>DC COMICS</h5>
                <a class="text-decoration-none" href="#">Characters</a>
                <a class="text-decoration-none" href="#">Comics</a>
                <a class="text-decoration-none" href="#">Movies</a>
                <a class="text-decoration-none" href="#">Tv</a>
                <a class="text-decoration-none" href="#">Games</a>
                <a class="text-decoration-none" href="#">Videos</a>
                <a class="text-decoration-none" href="#">News</a>
                
                
                <h5 class="pt-5">SHOP</h5>
                <a class="text-decoration-none pt-1" href="#">Shop DC</a>
                <a class="text-decoration-none" href="#">Shop DC Collectibles</a>

            </div>

            <!-- 2 div -->
            <div class="d-flex custom-width flex-column justify-content-start pt-4 me-3">
                <h5>DC</h5>
                <a class="text-decoration-none" href="#">Terms of Use</a>
                <a class="text-decoration-none" href="#">Privacy Policy</a>
                <a class="text-decoration-none" href="#">Ad Choices</a>
                <a class="text-decoration-none" href="#">Advertising</a>
                <a class="text-decoration-none" href="#">Jobs</a>
                <a class="text-decoration-none" href="#">Subscriptions</a>
                <a class="text-decoration-none" href="#">Talent Workshops</a>
                <a class="text-decoration-none" href="#">CPSC Certificates</a>
                <a class="text-decoration-none" href="#">Ratings</a>
                <a class="text-decoration-none" href="#">Shop Help</a>
                <a class="text-decoration-none" href="#">Contact us</a>

            </div>

            <!-- 3 div  -->
            <div class="d-flex custom-width flex-column justify-content-start pt-4 ">
                <h5>SITES</h5>
                <a class="text-decoration-none" href="#">DC</a>
                <a class="text-decoration-none" href="#">MAD Magazine</a>
                <a class="text-decoration-none" href="#">DC Kids</a>
                <a class="text-decoration-none" href="#">DC Universe</a>
                <a class="text-decoration-none" href="#">DC Power Visa</a>

            </div>

            <div class="d-flex justify-content-end custom-width-logo-footer">
                <img src="../assets/img/dc-logo-bg.png">
            </div>







        </section>


        <!-- Down part -->
    </footer>
</template>



<style lang="scss" scoped>
@use '../../src/assets/scss/partials/variables' as *;

#site_footer {

    .custom-bg-img {
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
    }

    .custom-width {
        width: 10%;
    }

    h5 {
        color: white;
    }

    a {
        color: $dc_footer_text;
    }

    .custom-width-logo-footer {
        width: 52%;
        margin: -50px 0;
        margin-left:200px;
    }
}
</style>