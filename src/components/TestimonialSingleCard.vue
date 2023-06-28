<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex direction-row justify-content-center px-5">
                <div v-for="card in TestimonialmultilpleCards" class="card d-flex direction-row px-3 me-5 "
                    style="width: 30rem;">
                    <img v-bind:srcset="card.src" class="card-img-top d-flex justify-content-center" alt="Card image">
                    <div class="card-body">
                        <h3 class="text-center">
                            {{ card.title }}
                        </h3>
                        <p class="card-text text-center">
                            {{ card.p }}
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

                                <!--!  QUESTO E' UN PROPS-->

<script>
export default {
    name: 'TestimonialSingleCard',
    data() {
        return {
            TestimonialmultilpleCards: [
                {
                    src: '../public/img/avada-movers-johndoe-final-200x200.jpg',
                    title: 'John Doe',
                    p: '"Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt beatae."',
                },

                {
                    src: '../public/img/avada-movers-janedoe-final-200x200.jpg',
                    title: 'Jane Doe',
                    p: ' "Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt beatae."',
                },

                {
                    src: '../public/img/avada-movers-johnsmith-final-200x200.jpg',
                    title: 'John Smith',
                    p: '"Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt beatae."',
                },

            ]
        }
    }
}
</script>


<style lang="scss">
img{
    width: 50px;
    height: 50px;
    border-radius: 50%;
}
</style>