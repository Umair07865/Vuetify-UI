<template>
    <div class=" d-flex flex-column outerMain">
  <div>
      <ul >
          <li>
              <div class="rounded-circle online green accent-3"></div>
              <div class="rounded-circle profilePic" ></div>

          </li>
          <li><h4>Dr.Riddle</h4></li>
          <li class="pl-2"><h6 >Scientist</h6></li>
      </ul>
  </div>
 <div style="    margin-top: 30rem;
   ">
     <ul>
         <li  class="mt-2">
         <!-- <div class="rounded-circle black white--text text-center pt-1" style="height:2rem;width:2rem"> -->
              <v-icon class="rounded-circle white black--text pa-2 ">
                mdi-draw-pen

            </v-icon>
             <!-- </div> -->
             </li>
         <li class="mt-2"> 
              <v-icon class="rounded-circle white  black--text pa-2 ">
                mdi-message-processing

            </v-icon>
         </li>
         <li class="mt-2">

              <v-icon class="rounded-circle black white--text pa-2 ">
                mdi-plus

            </v-icon>
         </li>
     </ul>
 </div>
    </div>
</template>
<script>
export default {
    name:'ColumnFourElements'
}
</script>
<style>
.outerMain{
    justify-content: space-between !important;
}
.outerMain ul{
    list-style: none;
}
.profilePic{
    background-image: url('https://faces-img.xcdn.link/thumb-lorem-face-2054_thumb.jpg');
    height: 3rem;
    width: 3rem;
    background-position: center;
    background-size: contain;
}
.online{
    height: 10px;
    width: 10px;
    position: relative;
    left: 2.4rem;
    top: 12px;
    outline: 2px solid white;
}
h6 {
  color: rgb(137, 137, 137);
}


</style>