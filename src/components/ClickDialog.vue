<template>
  <div class="text-center">
    <v-btn rounded="xl" id="no-background" @click="dialog = true">
      <v-icon class="mdi mdi-comment-question-outline"> </v-icon
    ></v-btn>

    <v-dialog v-model="dialog" width="auto">
      <v-card>
        <v-card-text class="pa-4">
          We are trying to answer your calls, emails and messages as soon as
          possible, but if it is something urgent, please call us on our private
          number.</v-card-text
        >
        <v-card-actions>
          <v-btn color="white" block @click="dialog = false"
            >Close Dialog</v-btn
          >
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
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
