<template>
    <div>
        <SecondaryTitle />
        <SingleCardService />

        <div class="container">
            <div class="row">
                <div class="col-12">

                </div>
            </div>
            <p>
                AppServiceSolution
            </p>
        </div>
    </div>
</template>


<script>
import SecondaryTitle from './SecondaryTitle.vue'
import SingleCardService from './SingleCardService.vue'

export default {
    name: 'AppServiceSolution',

    components: {
        SecondaryTitle,
        SingleCardService
    },
}
</script>


<style lang="scss">
</style>