<template>
    <div class="ease-bg">
        <div class="green-out-square">

            <div class="d-flex flex-row justify-content-center pt-5">
                <h6 class="uppercase-text text-white fw-bold">
                    we remove the headache from moving
                </h6>
            </div>

            <div class="d-flex flex-row justify-content-center pt-2">
                <p class="text-white fw-bold fs-1 text-capitalize">
                    move with ease
                </p>
            </div>

            <div class="d-flex flex-row justify-content-center">
                <div class="line"></div>
            </div>

            <div class="d-flex flex-row justify-content-center pt-3 ">
                <p class="text-white p-super p-in-green">
                    With our super simple service we can take you from getting a quote, right through to being in your new home with all of your belongings securely packed and safely delivered, even in the rooms of your choice.
                </p>
            </div>

            <div class="d-flex flex-row justify-content-center pt-3 ">
                <button type="button" class="my_btn-color my_btn"> GET A FREE QUOTE NOW</button>
            </div>




        </div>
    </div>
</template>


<script>
export default {
    name: 'AppEase',
}
</script>


<style lang="scss">
.ease-bg {
    height: 700px;
    background-image: url('/img/avada-movers-movewithease-background-new.jpg');
    background-size: cover;
}

.green-out-square {
    height: 400px;
    width: 600px;
    background-color: #6ABF17;
    border: 20px solid #5aa511;
    position: relative;
    top: 100px; 
    left: 800px;
}

.p-super{
    width: 450px;
}

.p-in-green{
    font-size: small;
    font-weight: bolder;
    line-height: 25px;
}

.line{
    height: 0.5px;
    width: 400px;
    border: 0.2px solid white;
}
</style>