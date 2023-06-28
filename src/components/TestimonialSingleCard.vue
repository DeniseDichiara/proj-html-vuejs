<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex direction-row justify-content-center px-5">
                <div v-for="card in TestimonialmultilpleCards" style="width: 30rem;">
                    <div class="d-flex flex-row justify-content-center mb-3">
                        <img v-bind:srcset="card.src" class="card-img-top d-flex justify-content-center ph" alt="Card image">
                    </div>
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
img.ph{
    width: 140px;
    height: 140px;
    border-radius: 50%;
}
</style>