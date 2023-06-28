<template>
    <div class="quote-bg">

        <div>
            <QuoteTitle />
        </div>
        <div class=" d-flex justify-content-center py-5 ">
            <button type="button" class=" my_btn-color my_btn">
                CLICK HERE
            </button>
        </div>
    </div>
</template>


<script>
import QuoteTitle from './QuoteTitle.vue';

export default {
    name: 'AppQuote',

    components: {
        QuoteTitle
    },
}
</script>


<style lang="scss">
.quote-bg {
    height: 500px;
    width: 1640px;
    background-image: url('/img/avada-movers-request-quote-background.jpg');
    background-size: cover;
}
</style>