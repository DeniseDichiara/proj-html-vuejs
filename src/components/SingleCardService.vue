<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex direction-row justify-content-center px-5">
                <div v-for="card in multilpleCards" class="card d-flex direction-row px-3 me-5 " style="width: 30rem;">
                    <div>
                        <img :src="card.src" class="card-img-top d-flex justify-content-center" alt="Card image">
                    </div>
                    
                    <div class="card-body">
                        <h3 class="text-center">
                            {{ card.title }}
                        </h3>
                        <p class="card-text text-center">
                            {{ card.p }}
                        </p>
                        <div>
                            <button type="button" class="my_btn-color my_btn d-flex justify-content-center mx-auto">Read
                                More</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'SingleCardService',
    data() {
        return {
            multilpleCards: [
                {
                    src: '../public/img/avada-movers-serviceonephoto-final.jpg',
                    title: 'Two Man Teams',
                    p: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt beatae.',
                },

                {
                    src: '../public/img/avada-movers-servicetwophoto-final.jpg',
                    title: 'We Do The Lifting',
                    p: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt beatae.',
                },

                {
                    src: '../public/img/avada-movers-servicethreephoto-final.jpg',
                    title: 'Cost To Cost',
                    p: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt beatae.',
                },

            ]
        }
    }
}
</script>


<style lang="scss"></style>