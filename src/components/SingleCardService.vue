<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex direction-row justify-content-center px-5">
                <div v-for="card in multilpleCards" class="card d-flex direction-row px-3 me-5" style="width: 30rem;">
                    <img src="card.img" class="card-img-top d-flex justify-content-center" alt="Card image">
                    <div class="card-body">
                        <h3 class="text-center">
                            {{ card.title }}
                        </h3>
                        <p class="card-text text-center">Some quick example text to build on the card title and make up the bulk of the
                            card's
                            content.</p>
                        <a href="#" class="btn btn-primary my_btn d-flex justify-content-center">Read More</a>
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
                    img: '',
                    title: 'Two Man Teams',
                    p: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt odio ipsum minima nisi eum quod harum, iste id porro beatae.',
                    button: 'Read More'
                },

                {
                    img: '',
                    title: 'We Do The Lifting',
                    p: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt odio ipsum minima nisi eum quod harum, iste id porro beatae.',
                    button: 'Read More'
                },

                {
                    img: '',
                    title: 'Cost To Cost',
                    p: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dicta cum amet soluta obcaecati, sequi natus. Recusandae dolorem sunt odio ipsum minima nisi eum quod harum, iste id porro beatae.',
                    button: 'Read More'
                },

            ]
        }
    }
}
</script>


<style lang="scss"></style>