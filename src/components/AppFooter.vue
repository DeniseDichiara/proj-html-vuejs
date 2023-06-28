<template>
    <footer>
        <div class="green-line"></div>

        <!--? ABOUT MOVERS POST-->

        <div class="container mb-5">
            <div class="row">
                <div class="col-12 d-flex direction-row justify-content-center mt-5">

                    <div class="d-flex justify-content-around">

                        <!--* ABOUT -->
                        <div class="movers-about">
                            <div>
                                <h4 class="footer-title">
                                    about
                                </h4>
                            </div>

                            <div>
                                <p class="lh-lg mb-5">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                    Placeat officiis, expedita beatae
                                    Placeat officiis, expedita
                                    beatae
                                </p>
                            </div>

                            <div>
                                <img src="/img/avada-movers-logo.png" alt="Avada Movers logo">
                            </div>
                        </div>

                        <!--? MOVERS -->
                        <div class="avada-movers link-avada">
                            <nav>
                                <h4 class="footer-title padding-title">
                                    avada movers
                                </h4>
                                <ul>
                                    <li v-for="link in navbarFooterLinks">
                                        <a :href="link.link" :class="active ? 'active' : ''">
                                            {{link.text}}
                                        </a>
                                    </li>
                                    
                                </ul>
                            </nav>
                        </div>

                        <!--! POST -->
                        <div class="avada-movers">
                            <nav>
                                <h4 class="footer-title padding-title">
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
                        </div>
                    </div>
                    <AppLowerFooter />
                </div>
            </div>
        </div>


        <div class="green-line-big">
            <div class="container">
                <div class="row">

                    <!--* FLEX-->
                    <div class="col-12">
                        <div class="footer-centrale d-flex flex-row justify-content-center pt-4">
                            <div class="d-flex flex-column ">
                                <p class="copyrights">
                                    <i class="fa-regular fa-copyright" style="color: #ffffff;"></i>
                                    Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights Reserved | Power by
                                    WordPress
                                </p>
                            </div>
                        </div>

                        <!--?   DIV SOCIAL-->
                        <div class="footer-centrale d-flex flex-row justify-content-center pt-2">

                            <div class="d-flex direction-row">
                                <div class="pe-3">
                                    <i class="fa-brands fa-facebook-f"></i>
                                </div>

                                <div class="pe-3">
                                    <i class="fa-brands fa-twitter"></i>
                                </div>

                                <div class="pe-3">
                                    <i class="fa-brands fa-instagram"></i>
                                </div>

                                <div class="pe-3">
                                    <i class="fa-brands fa-youtube"></i>
                                </div>
                            </div>
                        </div>
                    </div>

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
            navbarFooterLinks: [
                {
                    link: '#',
                    text: 'Home',
                    active: true
                },
                {
                    link: '#',
                    text: 'Rates',
                    active: true
                },
                {
                    link: '#',
                    text: 'Testimonials',
                    active: false
                },
                {
                    link: '#',
                    text: 'FAQ',
                    active: false
                },
                {
                    link: '#',
                    text: 'Blog',
                    active: false
                },
                {
                    link: '#',
                    text: 'Free Quote',
                    active: false
                },
            ]
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

.padding-title{
    padding-left: 35px;
}

h4 {
    margin-right: 4rem;
}

.movers-about{
    width: 300px;
    padding-right: 50px;
}

.link-avada{
    padding-right: 100px;
}

li{
    padding-left: 0;
}

li:hover{
    color: #6abf17;
}

.green-line-big {
    height: 150px;
    background-color: #6abf17;
    color: white;
}
</style>