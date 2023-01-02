<template id="outerTemplete">
  <v-app>
   

    <v-main style="margin-top:2rem">
     <OuterGrid/>
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import OuterGrid from './components/OuterGrid.vue';
export default {
  name: 'App',

  components: {
   OuterGrid
  },

 
};
</script>
<style>
#app{
   background-color:rgb(202,193,190);
  
}
</style>