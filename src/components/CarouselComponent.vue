<template>
    <v-carousel cycle height="400" hide-delimiter-background show-arrows="hover">
      <v-carousel-item v-for="(slide, i) in slides" :key="i">
        <v-sheet class="white" height="100%">
          <div class="d-flex fill-height justify-center align-center">
            <div class="text-h2 font-weight-medium grey--text">
              {{ slide }}
            </div>
          </div>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>
  </template>
  
  <script>
  export default {
    data () {
      return {
        slides: [
          'Accountability',
          'Respect',
          'Honesty',
          'Bravery',
          'Truth',
        ],
      }
    },
  }
  </script>
  <style></style>
  