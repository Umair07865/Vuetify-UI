<template>
    <div  >
               <img src="../assets/logo2.png" alt="loading" style="margin-left:1rem">
        <ul class="d-flex flex-column justify-space-around  unOrderList font-weight-bold ">
            <li> <span> <v-icon>
                mdi-chart-bar-stacked
            </v-icon> </span>  Dashboard</li>
            <li> <span> <v-icon>
                mdi-school
            </v-icon> </span>  Education</li>
       <!-- drop down list-->
            <li class="d-flex" style="gap:5px"> <span> <v-icon class="padding-top-2 " style="line-height:4rem"> 
                mdi-chart-bubble

            </v-icon> </span>    <v-select
            v-model="e6"
            
        :items="states"
        multiple
          chips
        :menu-props="{ bottom: true, offsetY: true }"
        label=" Resources" 
        class="dropdown">  
        
     
     </v-select></li>
            <li> <span>  <v-icon>
                mdi-cog

            </v-icon></span>  Settings</li>
            <li class="justify-end  " style="margin-top:15rem"> <span >  <v-icon class="rounded-circle black white--text pa-2 ">
                mdi-logout

            </v-icon></span>  Log out</li>
        </ul>
    </div>
</template>
<script>
export default {
    name:'ColumnOneElements',
    data () {
      return {
        e6: [],
        e7: [],
        states: [
          'Genetics 101', 'DNA synthesis', 'Events',
        ],
      }
    },
}
</script>