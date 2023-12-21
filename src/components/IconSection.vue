<template>
  <v-container flat>
    <div class="icon-section">
      <v-col align="center" justify="center">
        <v-row align="center" justify="center">
          <div>
            <v-btn
              class="ma-14 pa-14"
              color="gray"
              icon="mdi mdi-map-marker-radius"
            >
              <v-icon size="100" class="mdi mdi-account-outline"></v-icon>
            </v-btn>
            <p class="icon-text">Uniquely for you</p>
            <p class="text-caption">personal design</p>
          </div>

          <div>
            <v-btn
              class="ma-14 pa-14"
              color="gray"
              icon="mdi mdi-map-marker-radius"
            >
              <v-icon size="100" class="mdi mdi-check-circle-outline"></v-icon>
            </v-btn>
            <p class="icon-text">High quality</p>
            <p class="text-caption">good sources</p>
          </div>

          <div>
            <v-btn
              class="ma-14 pa-14"
              color="gray"
              icon="mdi mdi-map-marker-radius"
            >
              <v-icon size="100" class="mdi mdi-timer-sand"></v-icon>
            </v-btn>
            <p class="icon-text">Short waiting time</p>
            <p class="text-caption">always on time</p>
          </div>
        </v-row>
      </v-col>
    </div>
  </v-container>
</template>

<script lang="ts">
export default {
  data () {
    return {
      dialog: false,
    }
  },
}
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Pinyon+Script&display=swap");

.icon-text {
  font-family: "Pinyon Script", cursive;
  font-size: xx-large;
}
.icon-section {
  padding-bottom: 6rem;
}
</style>
