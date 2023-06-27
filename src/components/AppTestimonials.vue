<template>
    <div class="testimonial-bg">

        <TestimonialTitle />
        <TestimonialSingleCard />
    </div>
</template>


<script>
import TestimonialTitle from './TestimonialTitle.vue';
import TestimonialSingleCard from './TestimonialSingleCard.vue';


export default {
    name: 'AppTestimonials',

    components: {
        TestimonialTitle,
        TestimonialSingleCard,
    },
}

</script>


<style lang="scss" scoped>
.testimonial-bg {
    height: 500px;
    width: 1640px;
    background-image: url('/img/avada-movers-testimonial-background.jpg');
    background-size: cover;
}
</style>