<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';



export default {
  components: {AppMain, AppFooter, AppHeader},
};

</script>

<template>
  <div class="container">

    <!-- Header -->
    <app-header></app-header>
   


    <!-- Main -->
    <app-main></app-main>
   

    <!-- Footer -->
   <app-footer></app-footer>
   

  </div>
  
  
</template>

 
  


<style lang="scss">
*{
  margin: auto;
  padding: auto;
  box-sizing: border-box;
}


</style>
