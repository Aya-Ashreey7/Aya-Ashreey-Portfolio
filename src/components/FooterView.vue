<template>
  <v-footer >
    <v-card
      elevation="0"
      rounded="0"
      width="100%"
      class="bg-blue-grey-lighten-5 text-center py-12 mt-16"
    >
      <div class="section-title">
        <div>
          <h2>Get in Touch</h2>
        </div>
        <div style="width: 120px" class="mx-auto">
          <v-slider v-model="slider2" color="yellow"></v-slider>
        </div>
      </div>
      <v-card-text>
        <h2 class="mb-4">Aya Ashreey</h2>
        <router-link
          target="_blank"
          href="https://www.linkedin.com/in/aya-ashreey-284688167/"
        >
          <v-btn
            class="mx-4"
            icon="fa-brands fa-linkedin"
            variant="plain"
            color="black"
          ></v-btn
        ></router-link>

        <router-link
          target="_blank"
          href="https://github.com/Aya-Ashreey7"
        >
          <v-btn
            class="mx-4"
            icon="fa-brands fa-square-github"
            variant="plain"
            color="black"
          ></v-btn>
        </router-link>

  <router-link
          target="_blank"
          href="mailto:ayaashry68@gmail.com"
        >
         <v-btn
          class="mx-4"
          icon="fa-solid fa-envelope"
          variant="plain"
          color="black"
        ></v-btn>
        </router-link>
         <router-link
          target="_blank"
          href="tel:+20 1024094208"
        >
         <v-btn
          class="mx-4"
          icon="fa-solid fa-phone"
          variant="plain"
          color="black"
        ></v-btn>
        </router-link>
       
      </v-card-text>

      <v-card-text class="text-black">
        @ {{ new Date().getFullYear() }} —
        <strong>AAE IdeaPro All Rights Reserved</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  setup() {
    return {
      slider2: 50,
    };
  },
};
</script>

<style>
.v-footer {
  padding: 8px 0 !important;
}
</style>