<template>
  <v-col cols="12" class="padd text-center mt-16" id="projects">
    <div class="section-title mb-4">
      <div>
        <h2>Projects</h2>
      </div>
      <div style="width: 120px" class="ml-auto mr-auto">
        <v-slider v-model="slider2" color="yellow"></v-slider>
      </div>
    </div>
    <v-row>
      <!-- =============Ella Project============= -->
      <v-col cols="12" md="6">
        <v-card elevation="4" class="mx-auto w-75">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent" v-bind="props" style="overflow: hidden">
              <v-img
                height="200px"
                src="/project imgs/ella.PNG"
                cover
                :style="`width: 100 % ; height: 100%;  cursor:pointer; transition: 0.5s all ease-in-out;  scale: ${
                  isHovering ? 1.1 : 1
                }`"
              ></v-img>
            </div>
          </v-hover>
          <v-card-title> E-commere Ella Project </v-card-title>

          <div class="d-flex justify-center align-center ga-10 mt-2">
            <router-link
              target="_blank"
              href="https://github.com/Aya-Ashreey7/Ella-Project-E-Commerce-vue3"
            >
              <v-btn
                rounded="xs"
                elevation="4"
                color="yellow"
                prepend-icon="fa-brands fa-github"
                >Code</v-btn
              >
            </router-link>

            <router-link
              target="_blank"
              href="https://ayaashreey.github.io/Ella-Project-E-Commerce-vue3-/#/"
            >
              <v-btn rounded="xs" elevation="4" color="yellow">Live</v-btn>
            </router-link>
          </div>
          <v-card-actions>
            <v-btn color="yellow" text="About Project"></v-btn>

            <v-spacer></v-spacer>
            <v-btn
              :icon="
                show ? 'fa-solid fa-chevron-up' : 'fa-solid fa-chevron-down'
              "
              @click="show = !show"
            ></v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>

              <v-card-text>
                E-Commerce Web-App using Vue.js - vuetify - API
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>
      <!-- =============E-commere Pharmacy Project============= -->
      <v-col cols="12" md="6">
        <v-card class="mx-auto w-75">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent" v-bind="props" style="overflow: hidden">
              <v-img
                height="200px"
                src="/project imgs/ph-vue.PNG"
                cover
                :style="`width: 100 % ; height: 100%;  cursor:pointer; transition: 0.5s all ease-in-out;  scale: ${
                  isHovering ? 1.1 : 1
                }`"
              ></v-img>
            </div>
          </v-hover>
          <v-card-title> E-commere Pharmacy Project </v-card-title>

          <div class="d-flex justify-center align-center ga-10 mt-2">
            <router-link
              target="_blank"
              href="https://github.com/Aya-Ashreey7/PH-VueJs-Project"
            >
              <v-btn
                rounded="xs"
                elevation="4"
                color="yellow"
                prepend-icon="fa-brands fa-github"
                >Code</v-btn
              >
            </router-link>

            <router-link
              target="_blank"
              href="https://ayaashreey.github.io/PH-VueJS-Project/#/"
            >
              <v-btn rounded="xs" elevation="4" color="yellow">Live</v-btn>
            </router-link>
          </div>
          <v-card-actions>
            <v-btn color="yellow" text="About Project"></v-btn>

            <v-spacer></v-spacer>
            <v-btn
              :icon="
                show ? 'fa-solid fa-chevron-up' : 'fa-solid fa-chevron-down'
              "
              @click="show = !show"
            ></v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>

              <v-card-text>
                E-Commerce Web-App using Vue.js - vuetify - API -I18n
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>
    </v-row>
    <!-- =============Dashboard Project============= -->
    <v-row>
      <v-col cols="12" md="6">
        <v-card class="mx-auto w-75">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent" v-bind="props" style="overflow: hidden">
              <v-img
                height="200px"
                src="/project imgs/dashboard.PNG"
                cover
                :style="`width: 100 % ; height: 100%;  cursor:pointer; transition: 0.5s all ease-in-out;  scale: ${
                  isHovering ? 1.1 : 1
                }`"
              ></v-img>
            </div>
          </v-hover>
          <v-card-title> Dashboard </v-card-title>

          <div class="d-flex justify-center align-center ga-10 mt-2">
            <router-link
              target="_blank"
              href="https://github.com/Aya-Ashreey7/simple-Dashboard-vue"
            >
              <v-btn
                rounded="xs"
                elevation="4"
                color="yellow"
                prepend-icon="fa-brands fa-github"
                >Code</v-btn
              >
            </router-link>

            <router-link
              target="_blank"
              href="https://ayaashreey.github.io/simple-Dashboard-vue/#/homePage"
            >
              <v-btn rounded="xs" elevation="4" color="yellow">Live</v-btn>
            </router-link>
          </div>
          <v-card-actions>
            <v-btn color="yellow" text="About Project"></v-btn>

            <v-spacer></v-spacer>
            <v-btn
              :icon="
                show ? 'fa-solid fa-chevron-up' : 'fa-solid fa-chevron-down'
              "
              @click="show = !show"
            ></v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>

              <v-card-text> using Vue.js - Tailwind - HTML - CSS </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>
      <!-- ==============Vue TOdo List================== -->
      <v-col cols="12" md="6">
        <v-card class="mx-auto w-75">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent" v-bind="props" style="overflow: hidden">
              <v-img
                height="200px"
                src="/project imgs/todoListVue.PNG"
                cover
                :style="`width: 100 % ; height: 100%;  cursor:pointer; transition: 0.5s all ease-in-out;  scale: ${
                  isHovering ? 1.1 : 1
                }`"
              ></v-img>
            </div>
          </v-hover>
          <v-card-title> TO Do List </v-card-title>

          <div class="d-flex justify-center align-center ga-10 mt-2">
            <router-link
              target="_blank"
              href="https://github.com/Aya-Ashreey7/Vue3-Todo-List"
            >
              <v-btn
                rounded="xs"
                elevation="4"
                color="yellow"
                prepend-icon="fa-brands fa-github"
                >Code</v-btn
              >
            </router-link>

            <router-link
              target="_blank"
              href="https://ayaashreey.github.io/Vue3-Todo-List-Final/#/"
            >
              <v-btn rounded="xs" elevation="4" color="yellow">Live</v-btn>
            </router-link>
          </div>
          <v-card-actions>
            <v-btn color="yellow" text="About Project"></v-btn>

            <v-spacer></v-spacer>
            <v-btn
              :icon="
                show ? 'fa-solid fa-chevron-up' : 'fa-solid fa-chevron-down'
              "
              @click="show = !show"
            ></v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>

              <v-card-text>
                TO Do List Web-App using Vue.js - JavaScript - HTML - CSS
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>
    </v-row>
    <!-- ======================================================================================= -->
    <!-- =============js udemy course project============== -->
    <v-row>
      <v-col cols="12" md="6">
        <v-card class="mx-auto w-75">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent" v-bind="props" style="overflow: hidden">
              <v-img
                height="200px"
                src="/project imgs/udemyJSWebsite.PNG"
                cover
                :style="`width: 100 % ; height: 100%;  cursor:pointer; transition: 0.5s all ease-in-out;  scale: ${
                  isHovering ? 1.1 : 1
                }`"
              ></v-img>
            </div>
          </v-hover>
          <v-card-title> E-commere Project </v-card-title>

          <div class="d-flex justify-center align-center ga-10 mt-2">
            <router-link
              target="_blank"
              href="https://github.com/Aya-Ashreey7/Ecomerce-website-html-css-js"
            >
              <v-btn
                rounded="xs"
                elevation="4"
                color="yellow"
                prepend-icon="fa-brands fa-github"
                >Code</v-btn
              >
            </router-link>

            <router-link
              target="_blank"
              href="https://ayaashreey.github.io/Ecomerce-website-html-css-js/"
            >
              <v-btn rounded="xs" elevation="4" color="yellow">Live</v-btn>
            </router-link>
          </div>
          <v-card-actions>
            <v-btn color="yellow" text="About Project"></v-btn>

            <v-spacer></v-spacer>
            <v-btn
              :icon="
                show ? 'fa-solid fa-chevron-up' : 'fa-solid fa-chevron-down'
              "
              @click="show = !show"
            ></v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>

              <v-card-text
                >E-commere Project using JavaScript - HTML - CSS <br> A project is
                not based on a specific idea, but is a group of tasks that are
                not related to each other</v-card-text
              >
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>
      <!-- ================Js Todo List================ -->
      <v-col cols="12" md="6">
        <v-card class="mx-auto w-75">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent" v-bind="props" style="overflow: hidden">
              <v-img
                height="200px"
                src="/project imgs/jsTodoList.PNG"
                cover
                :style="`width: 100 % ; height: 100%;  cursor:pointer; transition: 0.5s all ease-in-out;  scale: ${
                  isHovering ? 1.1 : 1
                }`"
              ></v-img>
            </div>
          </v-hover>
          <v-card-title> TO Do List </v-card-title>

          <div class="d-flex justify-center align-center ga-10 mt-2">
            <router-link
              target="_blank"
              href="https://github.com/Aya-Ashreey7/To-Do-List-js"
            >
              <v-btn
                rounded="xs"
                elevation="4"
                color="yellow"
                prepend-icon="fa-brands fa-github"
                >Code</v-btn
              >
            </router-link>

            <router-link
              target="_blank"
              href="https://ayaashreey.github.io/To-Do-List/"
            >
              <v-btn rounded="xs" elevation="4" color="yellow">Live</v-btn>
            </router-link>
          </div>
          <v-card-actions>
            <v-btn color="yellow" text="About Project"></v-btn>

            <v-spacer></v-spacer>
            <v-btn
              :icon="
                show ? 'fa-solid fa-chevron-up' : 'fa-solid fa-chevron-down'
              "
              @click="show = !show"
            ></v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>

              <v-card-text>
                TO Do List Web-App using JavaScript - HTML - CSS
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>
    </v-row>
  </v-col>
</template>

<script>
export default {
  data: () => ({
    show: false,
  }),
  setup() {
    return {
      slider2: 50,
    };
  },
};
</script>

<style>
</style>