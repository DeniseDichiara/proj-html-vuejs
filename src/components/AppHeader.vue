<template>
    <header class="header-bg">
        <div class="callus">
            <SolcialNavbar />
        </div>
        <AppLinks/>
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="mx-auto my_make-it">
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
    height: 550px;
    width: 1640px;
    background-image: url('/img/avada-movers-homeherobackground-final.jpg');
    background-size: cover;
}

.my_make-it{
    margin-top: 60px;
    margin-bottom: 80px;
}
</style>