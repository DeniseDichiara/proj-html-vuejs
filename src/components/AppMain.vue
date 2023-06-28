<template>
    <main>
        <AppCallAction />
        <AppHeadache />
        <AppServiceSolution />
        <AppEase />
        <AppTestimonials />
        <AppQuote />
    </main>
</template>


<script>
import AppCallAction from './AppCallAction.vue';
import AppHeadache from './AppHeadache.vue';
import AppServiceSolution from './AppServiceSolution.vue';
import AppEase from './AppEase.vue';
import AppTestimonials from './AppTestimonials.vue';
import AppQuote from './AppQuote.vue';

export default {
    name: 'Main',
    data() {
        return {

        }
    },

    components: {
        AppCallAction,
        AppHeadache,
        AppServiceSolution,
        AppEase,
        AppTestimonials,
        AppQuote
    }
}
</script>


<style lang="scss">
    
</style>