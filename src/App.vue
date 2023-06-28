<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  data() {
    return {
    }
  },

  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <div class="fixed">
    <div class="pt-4 py-2 ">
      <div class="d-flex flex-row justify-content-center">
        <i class="fa-solid fa-cart-shopping"></i>
      </div>
      <div class="d-flex flex-row justify-content-center">
        <p>
          Buy Now
        </p>
      </div>
      

    </div>
  </div>

  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
@import "bootstrap/scss/bootstrap";
@import './styles/general.scss';

.fixed {
  position: fixed;
  top: 250px;
  right: 20px;
  width: 100px;
  background-color: white;
  border-radius: 10px;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
</style>
