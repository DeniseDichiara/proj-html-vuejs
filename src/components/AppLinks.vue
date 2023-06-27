<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex direction-row justify-content-between my-3">
                <div>
                    <img src="../assets/img/avada-movers-logo.png" alt="Avada Movers logo">
                </div>
                <div class="d-flex direction-row">
                    <nav>
                        <ul class="d-flex direction-row">
                            <li v-for="link in navbarLinks">
                                <a :href="link.link" :class="active ? 'active' : ''">
                                    {{link.text}}
                                </a>
                            </li>
                        </ul>
                    </nav>
                    <div>
                        <button type="button" class="btn btn-primary my_btn">FREE QUOTE</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'AppLinks',
    data() {
        return {
            navbarLinks: [
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
                    text: 'Contact',
                    active: false
                },
            ]
        }
    }
}
</script>


<style lang="scss">
    li{
        padding: 1rem;
        font-size: 0.9rem;
        font-weight: 600;


        transition: background-color 1s ease;
    }
</style>