<template>
    <header>
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

                        <h1 class=" fs-1 simple my_moving">
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
.p-grey {
    color: #777777;
    font-weight: bold;
    font-size: x-small;
}

.simple {
    font-size: 50rem;
    font-weight: bold;
    color: black;
}

.my_moving{
    display: flex;
    flex-direction: row;
    justify-content: center;
}
</style>