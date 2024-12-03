<template>
   <v-col cols="12" class="padd text-center mt-16 py-12 bg-blue-grey-lighten-5" id="education" >
        <div class="section-title mb-4">
          <div>
            <h2>Education</h2>
          </div>
          <div style="width: 120px" class="ml-auto mr-auto">
            <v-slider v-model="slider2" color="yellow"></v-slider>
          </div>
        </div>
        <v-card
          class="edu-scale mx-auto py-8 text-grey-darken-3"
          elevation="5"
          width="800"
        >
          <h2>Bachelor of computers and information ,Computer science</h2>
          <h3>Fayoum University</h3>
          <h4>Septamer 2016 - May 2020</h4>
        </v-card>
      </v-col>
</template>

<script>
export default {
 setup() {
    return {
      slider2: 50,
    };
  },
}
</script>

<style>
.edu-scale:hover {
  transition: all 1s;
  transform: scale(1.1);
}
</style>