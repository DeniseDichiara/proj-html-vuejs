<template>
    <header>
        <div class="callus">
            <SolcialNavbar />
        </div>
        <AppLinks />
        <div class= "mx-auto">
            <p class="p-grey text-uppercase">
                Moving without the hassle
            </p>

            <h1 class="simple">
                WE MAKE IT SIMPLE
            </h1>

            <p class="p-grey text-uppercase">
                Professional service with quality and customer satisfaction
            </p>
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
}

.simple{
    font-weight: 800;
    color: black;
}
</style>