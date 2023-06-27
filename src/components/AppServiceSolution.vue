<template>
    <div>
        <SecondaryTitle />
        <SingleCardService />

        <div class="container">
            <div class="row">
                <div class="col-12">

                </div>
            </div>
        </div>
    </div>
</template>


<script>
import SecondaryTitle from './SecondaryTitle.vue';
import SingleCardService from './SingleCardService.vue';
import axios from 'axios';

export default {
    name: 'AppServiceSolution',

    components: {
        SecondaryTitle,
        SingleCardService
    },

    //
    /*created() {
        axios.get('')
            .then(function (response) {
                console.log(response);
            })

            .catch(function (error) {
                console.log(error);
            });
    }*/
}
</script>


<style lang="scss"></style>