<template>
  <span>
    <ul>
      <li class="d-flex justify-space-between">
        <span>
          <h4>Today's Plan</h4>
          <h6>June 14th,2022</h6>
        </span>
        <v-icon class="rounded-circle black white--text pa-2 ">
                mdi-plus

            </v-icon>
      </li>
      <li class="mt-9">
        <h3>Sustainable development goals and</h3>
        <h3>health innovation</h3>
      </li>
      <li class="d-flex justify-space-between mt-5">
        <span class="d-flex">
          <div
            class="customIcon rounded-circle"
            style="
              background-image: url('https://faces-img.xcdn.link/thumb-lorem-face-2891_thumb.jpg');
              background-size: contain;
              background-position: center;
            "
          ></div>
          <div
            class="customIcon rounded-circle overlap"
            style="
              background-image: url('https://faces-img.xcdn.link/thumb-lorem-face-2054_thumb.jpg');
              background-size: contain;
              background-position: center;
            "
          ></div>
          <div
            class="customIcon rounded-circle overlap"
            style="
              background-image: url('https://faces-img.xcdn.link/thumb-lorem-face-4281_thumb.jpg');
              background-size: contain;
              background-position: center;
            "
          ></div>
          <div class="customIcon rounded-circle overlap orange lighten-5 pl-1">
            +5
          </div>
        </span>
        <div style="border-left: 1px solid silver" class="pl-3">
          <h6 class="black--text">Medi Team meeting</h6>
          <h6>13:30 - 14:50</h6>
        </div>
      </li>
    </ul>
    <v-col v-for="n in 1" :key="n" cols="12" sm="12">
      <v-card
        class="pa-6  d-flex flex-column"
        outlined
        tile
        style="
          background-image: url('https://img.rawpixel.com/s3fs-private/rawpixel_images/website_content/rm222batch5-kul-03.jpg?w=800&dpr=1&fit=default&crop=default&q=65&vib=3&con=3&usm=15&bg=F4F4F3&ixlib=js-2.2.1&s=08fbfb223887d33030e97becaf4e20dc');
          background-size: cover;
          background-position: center;
        "
      >
        <h3>Weekly report</h3>
        <h6>Track your performance</h6>

        <div
          style="
            background: transparent;
            border: 1px solid black;
            height: 2rem;
            width: 8rem;
          "
          class="text-center square rounded-0 ml-4 pt-1 mt-14"
        >
          VIEW REPORT
        </div>
      </v-card>
    </v-col>
    <span class="d-flex">
      <v-col v-for="n in 1" :key="n" cols="12" md="6">
        <v-card
          class="pa-2"
          outlined
          tile
          style="
            background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRBcmJW2alhqDaettUXM4SfEjfMXuYdyR-7EA&usqp=CAU');background-size:cover;background-position:center;height:22rem
          "
        >
          <h3>Study 78X</h3>
          <span class="d-flex">
            <v-icon class="rounded-circle black white--text pa-2" style="font-size:14px">
              mdi-clock-time-four-outline
            </v-icon>
            <h6 class="ml-2">In progress</h6>
          </span>
        </v-card>
      </v-col>
      <v-col
        v-for="n in 1"
        :key="n"
        cols="12"
        md="6"
       
      >
        <v-card class="pa-2" outlined tile  style="
          background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTaDjVcKjWRX330fJW8b38Q6hgxPPGM7sBgEA&usqp=CAU');background-size:cover;background-position:center;height:22rem
        ">
          <h3>Analysis</h3>
          <span class="d-flex">
            <v-icon class="rounded-circle black white--text pa-2" style="font-size:14px">
              mdi-check
            </v-icon>
            <h6 class="ml-2">Completed</h6>
          </span>
        </v-card>
      </v-col>
    </span>
  </span>
</template>
<script>
export default {
  name: "ColumnTwoElements",
};
</script>
<style scoped>
ul {
  list-style: none;
}
.customIcon {
  height: 2rem;
  width: 2rem;
  border: 2px solid white;
}
.overlap {
  margin-left: -10px;
}
h6 {
  color: rgb(137, 137, 137);
}
</style>
