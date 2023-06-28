<template>
    <footer>
        <div class="green-line"></div>

        <div class="movers-about">
            <h4 class="footer-title">
                about
            </h4>
            <p class="lh-lg">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat officiis, expedita beatae tenetur accusamus
                optio consequatur ad earum excepturi voluptas aspernatur magni sed praesentium aliquam id possimus saepe vel
                ab.
            </p>
            <img src="/img/avada-movers-logo.png" alt="Avada Movers logo">
        </div>

        <nav class="avada-movers">
            <h4 class="footer-title">
                avada movers
            </h4>
            <ul>
                <!--! CICLARE CON V-FOR-->

                <li>Home</li>
                <li>Rates</li>
                <li>Testimonials</li>
                <li>Blog</li>
                <li>Free Quote</li>
            </ul>
        </nav>
        <AppLowerFooter />

        <nav class="avada-movers">
            <h4 class="footer-title">
                recent posts
            </h4>
            <ul>

                <!--! CICLARE CON V-FOR-->
                <li class="text-capitalize"> > heading out to college?</li>
                <li class="text-capitalize"> > moving your business?</li>
                <li class="text-capitalize"> > outsanding quality</li>
                <li class="text-capitalize"> > cost of moving</li>
                <li class="text-capitalize"> > best moving tips</li>
            </ul>
        </nav>

        <div class="green-line-big">
            <div class="d-flex flex-column ">
                <p class="copyrights">
                    <i class="fa-regular fa-copyright" style="color: #ffffff;"></i>
                    Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights Reserved | Power by WordPress
                </p>

            </div>
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


        
    </footer>
</template>


<script>
import AppLowerFooter from './AppLowerFooter.vue';

export default {
    name: 'Footer',
    data() {
        return {

        }
    },

    comments: {
        AppLowerFooter,
    },
}
</script>


<style lang="scss">
.green-line {
    height: 15px;
    background-color: #6abf17;
}

.footer-title {
    font-weight: bold;
    text-transform: uppercase;
}

.green-line-big{
    height: 150px;
    background-color: #6abf17;
    color: white;
}

</style>