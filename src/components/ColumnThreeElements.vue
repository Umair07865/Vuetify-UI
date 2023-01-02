<template>
   <span>
        <div style="padding:1rem">
        <span class="d-flex justify-space-between">
             <h4>Monthly pinned</h4>
             <h5>View all</h5>
        </span>
    </div>

     <div style="border:1px solid black;padding:1rem"  class="mt-3 tablediv">
        <span class="d-flex justify-space-between">
             <h4>Next-gen immuno</h4>
             <h5>5d</h5>
        </span>
        <h3>Multispecific liquids analysis</h3>
        <span class="d-flex justify-space-arround">
              <v-icon class="rounded-circle black white--text pa-2 icons ">
                mdi-numeric-1

            </v-icon>
             <h4 class="ml-2">Next-gen feedback</h4>
             
        </span>
    </div>
      <div style="border:1px solid black;padding:1rem"  class="mt-3 tablediv">
        <span class="d-flex justify-space-between">
             <h4>Harmony</h4>
             <h5>1d</h5>
        </span>
        <h3>Protein characterization during childhood </h3>
         <h3>and pregnancy</h3>
        <span class="d-flex justify-space-arround">
            <v-icon class="rounded-circle black white--text pa-2  icons">
                mdi-exclamation

            </v-icon>
             <h4 class="ml-2">Deadline is today</h4>
             
        </span>
    </div>
      <div style="border:1px solid black;padding:1rem" class="mt-3 tablediv">
        <span class="d-flex justify-space-between">
             <h4>Pharmaceutical</h4>
             <h5>7d</h5>
        </span>
        <h3>Qucik element dissolution testing</h3>
        <span class="d-flex justify-space-arround">
             <v-icon class="rounded-circle black white--text pa-2  icons ">
                mdi-check

            </v-icon>
             <h4 class="ml-2">Accepted</h4>
             
        </span>
    </div>
     <div style="padding:1rem"  >
        <span class="d-flex justify-space-between">
             <h4>My learnings</h4>
             <h5>...</h5>
        </span>
        <h4>Your progress of medical lectures</h4>

        <span class="gridSystem  mt-4" >
            <div class="tablediv" >
                <table>
                     <tr>
                     <td rowspan="2" class="backImagesCards" id="virusimg">

                     </td>
                     <td>Viruses</td>
                     </tr>

                     <tr>
                     <td> <h6>96% progress</h6>
                     </td>
                     </tr>
                 </table>
            </div>
            <div class="tablediv">
                <table>
                     <tr>
                     <td rowspan="2" class="backImagesCards" id="bacteriaImg">

                     </td>
                     <td>Bacterial cells</td>
                     </tr>

                     <tr>
                     <td> <h6>33% progress</h6>
                     </td>
                     </tr>
                 </table>
            </div>
            <div class="tablediv">
                 <table>
                     <tr>
                     <td rowspan="2" class="backImagesCards" id="medSciences">

                     </td>
                     <td>Med science</td>
                     </tr>

                     <tr>
                     <td> <h6>7% progress</h6>
                     </td>
                     </tr>
                 </table>
            </div>
            <div class="tablediv">
                <table>
                     <tr>
                     <td rowspan="2" class="backImagesCards" id="humanImg">

                     </td>
                     <td>Humang gens</td>
                     </tr>

                     <tr>
                     <td> <h6>58% progress</h6>
                     </td>
                     </tr>
                 </table>
            </div>
        </span>

    </div>
   </span>
</template>
<script>

export default {
    name:'ColumnThreeElements'
}
</script>
<style scoped>
h5 {
  color: rgb(137, 137, 137);
}
h6 {
  color: rgb(137, 137, 137);
}
h4{
    color: rgb(137, 137, 137);
}
.gridSystem{
display: grid;
grid-template-rows: repeat(2,6rem);

grid-template-columns: repeat(2,10.5rem);
}
.tablediv{
    transition: ease 2s;
}
.tablediv:hover{
  transform: scale(1.1);
}


.backImagesCards{
    height: 3rem;
    width: 3rem;
    background-size: contain;
    background-position: center;   

}
#humanImg{
    background-image: url('humangenimg.png');
}
#virusimg{
    background-image: url('virusimg.png');
}
#medSciences{
    background-image: url('medSciences.png');
}
#bacteriaImg{
    background-image: url('bacteriaimg.png');
}
.icons{
    font-size: 15px;
}
</style>