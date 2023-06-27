<template>
    <header>
        <div class="callus">
            <SolcialNavbar />
        </div>
        <AppLinks />
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
    
</style>