<template>
    <v-col cols="12" class="padd text-center py-12 mt-16 bg-blue-grey-lighten-5" id="skills">
        <div class="section-title mb-4">
          <div>
            <h2>Skills</h2>
          </div>
          <div style="width: 120px" class="ml-auto mr-auto">
            <v-slider v-model="slider2" color="yellow"></v-slider>
          </div>
        </div>
        <v-row class="mx-8">
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-html5
                </v-icon>
                <span class="skills-name">HTML</span>
              </v-col>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-css3
                </v-icon>
                <span class="skills-name">CSS</span>
              </v-col>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="mx-8">
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-js
                </v-icon>
                <span class="skills-name">JavaScript</span>
              </v-col>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center text-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-bootstrap
                </v-icon>
                <span class="skills-name">Bootstrap</span>
              </v-col>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="mx-8">
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-wordpress
                </v-icon>
                <span class="skills-name">WordPress</span>
              </v-col>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-vuejs
                </v-icon>
                <span class="skills-name">Vue.js</span>
              </v-col>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="mx-8">
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-vuejs
                </v-icon>
                <span class="skills-name">Vuex</span>
              </v-col>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  <svg
                    width="512"
                    height="512"
                    viewBox="0 0 512 512"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M281.44 397.667H438.32C443.326 397.667 448.118 395.908 452.453 393.427C456.789 390.946 461.258 387.831 463.76 383.533C466.262 379.236 468.002 374.36 468 369.399C467.998 364.437 466.266 359.563 463.76 355.268L357.76 172.947C355.258 168.65 352.201 165.534 347.867 163.053C343.532 160.573 337.325 158.813 332.32 158.813C327.315 158.813 322.521 160.573 318.187 163.053C313.852 165.534 310.795 168.65 308.293 172.947L281.44 219.587L227.733 129.13C225.229 124.834 222.176 120.307 217.84 117.827C213.504 115.346 208.713 115 203.707 115C198.701 115 193.909 115.346 189.573 117.827C185.238 120.307 180.771 124.834 178.267 129.13L46.8267 355.268C44.3208 359.563 44.0022 364.437 44 369.399C43.9978 374.36 44.3246 379.235 46.8267 383.533C49.3288 387.83 53.7979 390.946 58.1333 393.427C62.4688 395.908 67.2603 397.667 72.2667 397.667H171.2C210.401 397.667 238.934 380.082 258.827 346.787L306.88 263.4L332.32 219.587L410.053 352.44H306.88L281.44 397.667ZM169.787 352.44H100.533L203.707 174.36L256 263.4L221.361 323.784C208.151 345.387 193.089 352.44 169.787 352.44Z"
                      fill="#2196F3"
                    />
                  </svg>
                </v-icon>
                <span class="skills-name">Nuxt.js</span>
              </v-col>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="mx-8">
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="5">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-square-github
                </v-icon>
                <span class="skills-name">GitHub</span>
              </v-col>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card class="mx-auto py-2 text-grey-darken-3 w-75" elevation="4">
              <v-col class="d-flex align-center edu-scale2">
                <v-icon class="skills-icon mr-2 ml-4" color="blue">
                  fa-brands fa-git-alt
                </v-icon>
                <span class="skills-name">Git</span>
              </v-col>
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
.edu-scale2:hover {
  transition: all 1s;
  transform: scale(1.05);
}
</style>