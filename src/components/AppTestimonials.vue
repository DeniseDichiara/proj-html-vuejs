<template>
    <div class="testimonial-bg">

        <TestimonialTitle />
    </div>
</template>


<script>
import TestimonialTitle from './TestimonialTitle.vue';

export default {
    name: 'AppTestimonials',

    components: {
        TestimonialTitle,
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