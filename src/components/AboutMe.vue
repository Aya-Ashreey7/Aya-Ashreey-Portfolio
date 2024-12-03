<template>
    <v-col cols="12" class="mt-16" id="about">
        <v-row>
          <v-col cols="12" sm="6">
            <div class="egg">
              <v-img src="i2.png" max-height="300" class=""></v-img>
            </div>
          </v-col>

          <v-col cols="12" sm="6">
            <h2 class="mt-16">About Me</h2>
            <div style="width: 120px">
              <v-slider v-model="slider2" color="yellow"></v-slider>
            </div>
            <h4 class="mt-n4">I Am a Creative Front-End Developer</h4>

            <p class="text-grey">
              I have experience in Front end like (Vue-js, Nuxt-js) and I am
              interested in solving software problems , I work hard for
              self-realization in it and I am always learning new things
              ,Developed responsive websites and web applications, Optimized
              websites for cross-browser compatibility and mobile responsiveness
            </p>
            <br />
            <p class="text-grey">
              Seeking a position as a Front-End Developer in an ambitious and
              dynamic company where I can contribute my skills, learn new
              technologies, and grow professionally.
            </p>

            <v-btn @click="downloadCV" tile dark color="yellow" class="mt-4">
              Download CV
            </v-btn>
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
  methods:{
    downloadCV() {
      // Path to your CV file
      const cvPath = "/cv/Aya_Ashreey_CV.pdf"; // Replace with your actual file path
      // Create a temporary anchor element
      // window.open(cvPath, '_blank');
      const link = document.createElement("a");
      link.href = cvPath;
      link.setAttribute("download", "Aya_Ashreey_CV.pdf"); // Specify the downloaded file name
      document.body.appendChild(link);
      link.click();
      document.body.removeChild(link);
    },
  }
}
</script>

<style>
.egg {
  display: block;
  margin-left: 100px;
  margin-top: 50px;
  width: 356px;
  height: 300px;
  background-color: #fbdf7e;
  border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}
</style>