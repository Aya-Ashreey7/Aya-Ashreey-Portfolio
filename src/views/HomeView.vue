<template>
  <v-app id="home">
    <NavBar />
    <v-container fluid>
      <div class="head position-relative text-center p-3 mb-2 w-100 text-white">
        <v-row>
          <v-col cols="5">
            <div style="position: relative" class="mt-16">
              <h1 class="text-grey">Hello,</h1>
              <h1 class="text-white">I'M Aya Ashreey</h1>
              <span class="text-grey">Front-End Developer</span><br />

              <v-btn
                @click="scroll('footer')"
                tile
                dark
                class="text-yellow mt-8"
                variant="outlined"
              >
                Contact me
              </v-btn>
            </div>
          </v-col>

          <v-col cols="2">
            <div
              style="
                position: absolute;
                z-index: 9999;
                bottom: 0;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
              class="mt-16"
            >
              <v-icon>fas fa-angle-double-down</v-icon>
            </div>
          </v-col>

          <v-col cols="5">
            <div style="position: relative; z-index: 9999" class="mt-16">
              <v-img src="i1.png" contain max-height="300"></v-img>
            </div>
          </v-col>
        </v-row>
      </div>
      <AboutMe />

      <EducationComp />

      <ExperienceComp />

      <SkillsComp />

      <ProjectsComp />
    </v-container>
    <div id="footer">
      <FooterView />
    </div>
  </v-app>
</template>

<script>
import { defineComponent } from "vue";
import NavBar from "../components/NavBar.vue";
import FooterView from "../components/FooterView.vue";
import AboutMe from "@/components/AboutMe.vue";
import EducationComp from "@/components/EducationComp.vue";
import ExperienceComp from "@/components/ExperienceComp.vue";
import SkillsComp from "@/components/SkillsComp.vue";
import ProjectsComp from "@/components/ProjectsComp.vue";
export default defineComponent({
 
  name: "HomeView",
  setup() {
    return {
      slider2: 50,
    };
  },
  components: {
    NavBar,
    AboutMe,
    EducationComp,
    ExperienceComp,
    SkillsComp,
    ProjectsComp,
    FooterView,
  },
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
});
</script>
<style scoped>
.v-container {
  padding: 16px 0 16px 0;
}
.head {
  height: 400px;
}
.head:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, 6deg);
}
.head:after {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, -6deg);
}


</style>
