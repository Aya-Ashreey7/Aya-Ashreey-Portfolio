<template>
   <v-app-bar color="black" dark flat class="px-12">
    <v-btn >
        <v-icon color="yellow" left class="mr-2">fas fa-signature</v-icon> Aya
      </v-btn>

<v-spacer></v-spacer>
      <v-btn text @click="scroll('home')" class="text-yellow">Home</v-btn>
      <v-btn text @click="scroll('about')"  >About</v-btn>
      <v-btn text @click="scroll('education')"  >Education</v-btn>
      <v-btn text @click="scroll('experience')" > Experience</v-btn>
      <v-btn text @click="scroll('skills')"  > Skills</v-btn>
      <v-btn text @click="scroll('projects')"  > Projects</v-btn>
      <v-btn text @click="scroll('contact')"  > Contact</v-btn>
   </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style>
</style>