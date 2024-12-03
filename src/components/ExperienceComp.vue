<template>
   <v-col cols="12" class="padd text-center py-12 mt-16" id="experience">
        <div class="section-title mb-4">
          <div>
            <h2>Experience</h2>
          </div>
          <div style="width: 120px" class="ml-auto mr-auto">
            <v-slider v-model="slider2" color="yellow"></v-slider>
          </div>
        </div>
        <v-row class="mx-8">
          <v-col cols="12" md="6">
            <v-card
              class="edu-scale mx-auto py-8 text-grey-darken-3 w-75"
              elevation="5"
            >
              <h2>Front End Developer</h2>
              <h3>Murabba dev Company</h3>
              <h4>2023-2024</h4>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card
              class="edu-scale mx-auto py-8 text-grey-darken-3 w-75"
              elevation="5"
            >
              <h2>Full Stack Developer</h2>
              <h3>Life Makers Association</h3>
              <h4>2021-2023</h4>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="mx-8">
          <v-col cols="12" md="6">
            <v-card
              class="edu-scale mx-auto py-8 text-grey-darken-3 w-75"
              elevation="5"
            >
              <h2>Technical Support Engineer</h2>
              <h3>WE Company</h3>
              <h4>2021-2021</h4>
            </v-card>
          </v-col>

          <v-col cols="12" md="6">
            <v-card
              class="edu-scale mx-auto py-8 text-grey-darken-3 w-75"
              elevation="5"
            >
              <h2>Front-end developer</h2>
              <h3>Turnkey web solutions company</h3>
              <h4>2020-2021</h4>
            </v-card>
          </v-col>
        </v-row>
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