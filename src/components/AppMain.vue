<script>
import AppComics from './AppComics.vue';

export default {

    name: 'AppMain',

    components: {
        AppComics
    },

    data() {
        return {
            // serviceArray: [
            //     { title: 'DIGITALS COMICS', image: '../../src/assets/img/buy-comics-digital-comics.png' },
            //     { title: 'DC MERCHANDISE', image: '../../src/assets/img/buy-comics-merchandise.png' },
            //     { title: 'SUBCRIPTION', image: '../../src/assets/img/buy-comics-subscriptions.png' },
            //     { title: 'COMIC SHOP LOCATOR', image: '../../src/assets/img/buy-comics-shop-locator.png' },
            //     { title: 'DC POWER VISA', image: '../../src/assets/img/buy-dc-power-visa.svg' }
            // ]
        }
    }
}
</script>

<!-- TO DO :RENDERE DINAMICI LE IMMAGINI DEI SERVIZI -->
<template>
    <main id="site_main">

        <!-- CONTENT GOES HERE IN PROGRESS -->
        <section id="content_here">
           <AppComics></AppComics>
        </section>
        <!-- /#content -->

        <section id="site_menu">
            <div class="container">
                <ul class="list-unstyled d-flex justify-content-around align-items-center py-5">
                    <li class="d-flex align-items-center">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-digital-comics.png"
                                    alt="">
                            </div>
                            <span class="text-white text-nowrap">DIGITAL COMICS</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-merchandise.png"
                                    alt="">
                            </div>
                            <span class="text-white text-nowrap">DC MERCHANDISE</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-subscriptions.png"
                                    alt="">
                            </div>
                            <span class="text-white">SUBSCRIPTION</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-shop-locator.png"
                                    alt="">
                            </div>
                            <span class="text-white text-nowrap">COMIC SHOP LOCATOR</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center ps-4">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div class="power_visa">
                                <img class="img-fluid w-75" style="height: 50px;" src="../assets/img/buy-dc-power-visa.svg"
                                    alt="">
                            </div>
                            <span class="text-white text-nowrap ps-2">DC POWER VISA</span>
                        </a>
                    </li>


                </ul>
            </div>

        </section>


    </main>
</template>


<style lang="scss" scoped>
@use '../../src/assets/scss/partials/variables' as *;

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

#site_main {

    #content_here {
        background-color: $dc_dark;
        color: $dc_white;
    }

    #site_menu {
        background-color: $dc_main_blue;

        .power_visa {
            max-height: 62px;
        }
    }



}
</style>