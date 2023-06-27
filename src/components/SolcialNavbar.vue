<template>
    <div class="container ">
        <div class="row">
            <div class="col-12 d-flex direction-row justify-content-between my-3">
                <div class="d-flex direction-row">
                    <div class="pe-2">
                        <i class="fa-solid fa-phone-flip"></i>
                    </div>
                    <p>
                        Call us for a Free Quote: 1.800.555.6789
                    </p>
                </div>

                <!--* FARLO DIVENTARE UN ARRAY-->
                <!--? fare cmponet icons-->
                <div class="d-flex direction-row">
                    <div class="pe-3">
                        <i class="fa-brands fa-facebook-f" ></i>
                    </div>

                    <div class="pe-3">
                        <i class="fa-brands fa-twitter"></i>
                    </div>

                    <div class="pe-3">
                        <i class="fa-brands fa-instagram" ></i>
                    </div>

                    <div class="pe-3">
                        <i class="fa-brands fa-youtube" ></i>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'SolcialNavbar',
    data() {
        return {
            
        }
    }
}
</script>


<style lang="scss">

   //@use '../styles/partials/mixins' as *; 
    
    .callus{
        background-color: #6abf17;
        color: white;
        height: 60px;
    }

    i:hover{
        color: lightgrey;
    }
</style>