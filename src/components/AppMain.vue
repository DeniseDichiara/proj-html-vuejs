<template>
    <main>
        <p>
        </p>
        <AppCallAction />
        <AppHeadache />
        <AppServiceSolution />
        <AppEase />
        <AppTestimonials />
    </main>
</template>


<script>
import AppCallAction from './AppCallAction.vue';
import AppHeadache from './AppHeadache.vue';
import AppServiceSolution from './AppServiceSolution.vue';
import AppEase from './AppEase.vue';
import AppTestimonials from './AppTestiomonials.vue';


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
        AppTestimonials
    }
}
</script>


<style lang="scss">
    
</style>