<template>
    <div class="testimonial-bg">
        <div>
            <TestimonialTitle />
            <TestimonialSingleCard />
        </div>

        <div class=" d-flex justify-content-center py-5">
            <button type="button" class=" my_btn-color my_btn">
                READ MORE TESTIMONIALS
            </button>
        </div>
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
    height: 700px;
    width: 1640px;
    background-image: url('/img/avada-movers-testimonial-background.jpg');
    background-size: cover;
}
</style>