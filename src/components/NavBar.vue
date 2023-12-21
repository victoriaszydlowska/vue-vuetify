<template>
  <v-app-bar
    app
    color="grey lighten-4
"
  >
    <v-toolbar-title class="ml-5">
      <strong>We<span id="font">Day</span></strong>
    </v-toolbar-title>

    <v-spacer></v-spacer>
    <div class="px-2">
      <router-link to="/" class="router text-decoration-none px-2"
        >Home
      </router-link>

      <router-link to="/about" class="router text-decoration-none px-2"
        >About</router-link
      >
    </div>

    <v-badge color="#FF6D59" overlap content="5" class="mr-3 mt-1">
      <v-avatar color="grey lighten-3" size="35">
        <v-icon x-small color="#FF6D59">far fa-heart</v-icon>
      </v-avatar>
    </v-badge>
    <v-badge color="#FF6D59" overlap content="1" class="mr-3 mt-1">
      <v-avatar color="grey lighten-3" size="35">
        <v-icon small color="#FF6D59">mdi-basket</v-icon>
      </v-avatar>
    </v-badge>

    <v-avatar size="30" class="ml-3">
      <v-img
        src="https://th.bing.com/th/id/OIP.EneRpxAQ9Q1e8LP_GuQHigAAAA?rs=1&pid=ImgDetMain"
      ></v-img>
    </v-avatar>
    <v-btn icon dark>
      <v-icon x-small color="#878A94">fas fa-chevron-down</v-icon>
    </v-btn>
  </v-app-bar>
</template>
<script>
export default {

}
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Pinyon+Script&display=swap");

.router {
  color: #757575 !important;
}
#font {
  font-family: "Pinyon Script", cursive;
  font-size: xx-large;
}
</style>
