<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';



export default {
  components: {AppMain, AppFooter, AppHeader},
};

</script>

<template>
  <app-header></app-header>

  <main>
    <app-main></app-main>
  </main>

  <app-footer></app-footer>
</template>

<style lang="scss" scoped>
*{
  margin: auto;
  padding: auto;
  box-sizing: border-box;
}
</style>
