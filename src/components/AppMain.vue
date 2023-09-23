<script>
export default {
    name: 'AppMain'
}
</script>

<template>
    <main id="site_main">

        <!-- CONTENT GOES HERE IN PROGRESS -->
        <section id="content_here">
            <div class="container">
                <h2 class="py-5">----- Content goes here------</h2>
            </div>
            <!-- /.container -->
        </section>
        <!-- /#content -->

        <section id="site_menu">
            <div class="container">
                <ul class="list-unstyled d-flex justify-content-around align-items-center py-5">
                    <li class="d-flex align-items-center p-3">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-digital-comics.png"
                                    alt="">
                            </div>
                            <span class="text-white">DIGITAL COMICS</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center p-3">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-merchandise.png"
                                    alt="">
                            </div>
                            <span class="text-white">DC MERCHANDISE</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center p-3">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-subscriptions.png"
                                    alt="">
                            </div>
                            <span class="text-white">SUBSCRIPTION</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center p-3">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div>
                                <img class="img-fluid" style="width: 40%;" src="../assets/img/buy-comics-shop-locator.png"
                                    alt="">
                            </div>
                            <span class="text-white">COMIC SHOP LOCATOR</span>
                        </a>
                    </li>
                    <li class="d-flex align-items-center p-3">
                        <a href="#" class="d-flex align-items-center text-decoration-none">
                            <div class="power_visa">
                                <img class="img-fluid" style="height: 50px;" src="../assets/img/buy-dc-power-visa.svg"
                                    alt="">
                            </div>
                            <span class="text-white">DC POWER VISA</span>
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



}</style>