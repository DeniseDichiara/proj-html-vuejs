<template>
    <header class="header-bg">
        <div class="callus">
            <SolcialNavbar />
        </div>
        <AppLinks />
        <div class="container pt-5">
            <div class="row">
                <div class="col-12">
                    <div class="mx-auto">
                        <p class="p-grey text-uppercase my_moving">
                            Moving without the hassle
                        </p>

                        <h1 class=" simple my_moving">
                            WE MAKE IT SIMPLE
                        </h1>

                        <p class="p-grey text-uppercase my_moving">
                            Professional service with quality and customer satisfaction
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-12 mb-5"></div>
            <div class="col-12 mb-5"></div>
        </div>


    </header>
</template>


<script>
import SolcialNavbar from './SolcialNavbar.vue';
import AppLinks from './AppLinks.vue';

export default {
    name: 'Header',
    data() {
        return {

        }
    },

    components: {
        SolcialNavbar,
        AppLinks,
    },
}
</script>


<style lang="scss">
.header-bg{
    background-image: url('/img/avada-movers-homeherobackground-final.jpg');
}
</style>