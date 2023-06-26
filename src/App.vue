<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/.vue';

export default {
    name: 'App',
    data() {
        return {
        }
    },

    components: {
    AppHeader,
    AppMain,
    Footer
  }
}

</script>

<template>
  
  <AppHeader/>
  <AppMain/>
  <AppFooter/>
</template>

<style lang="scss">
@import './styles/general.scss';

</style>
