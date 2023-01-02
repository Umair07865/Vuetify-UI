<template >
     <v-container id="container">
   <v-row no-gutters style="background-color:#FAF7F4">
     <!-- first column-->
    <v-col
        v-for="n in 1"
        :key="n"
        cols="12"
        sm="3"

       
      >
        <v-card
          class="pa-2 card  "
          
          tile
          
        >
    <ColumnOneElements/>
        
        </v-card>
       
      </v-col>
      <!-- column 2-->
      <v-col
        v-for="n in 1"
        :key="n"
        cols="12"
        sm="4"
      >
        <v-card
          class="pa-2 card"
          
          tile
        >
        <ColumnTwoElements/>
        </v-card>
      </v-col>
      <!--column 3-->
      <v-col
        v-for="n in 1"
        :key="n"
        cols="12"
        sm="4"
      >
        <v-card
          class="pa-2 card"
         orange
          tile
        >
        <ColumnThreeElements/>
        </v-card>
      </v-col>
      <!--column 4-->
      <v-col
        v-for="n in 1"
        :key="n"
        cols="12"
        sm="1"
        style="border:none"
      >
        <v-card
          class=" card"
         theme--none
          tile
        >
          <ColumnFourElements/>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
import ColumnOneElements from './ColumnOneElements.vue';
import ColumnTwoElements from './ColumnTwoElements.vue';
import ColumnThreeElements from './ColumnThreeElements.vue';
import ColumnFourElements from './ColumnFourElements.vue';
export default {
    name:'OuterGrid',
    
    components:{
      ColumnOneElements,
      ColumnTwoElements,
      ColumnThreeElements,
      ColumnFourElements
    }
}
</script>
<style>
.unOrderList{
    list-style: none;
    gap:1px;
   
  
}
body{
  background-color: rgb(237, 230, 226);
}
.unOrderList li {
    line-height: 3rem;

}
.unOrderList li:hover{
  background-color: rgb(237, 230, 226);
}
.card{
  height:800px;
  background-color:rgba(250, 247, 244);
}
#container{
  background-color:rgb(202,193,190);
}


</style>
   