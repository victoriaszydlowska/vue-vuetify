<template>
  <v-footer
    class="bg-indigo-lighten-1 text-center d-flex flex-column "
  >

    <v-col class="ma-1 pa-1">
      <v-row align="center" justify="center"  >
<v-icon class="ma-2 pa-2 mdi mdi-facebook"></v-icon>
<v-icon class="ma-2 pa-2 mdi mdi-instagram" ></v-icon>
<v-icon class="ma-2 pa-2 mdi mdi-twitter"></v-icon>
</v-row>
</v-col>



    <v-divider></v-divider>

    <div>
      {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
    </div>
  </v-footer>
</template>
<script>
export default {
data: () => ({

}),
}
</script>