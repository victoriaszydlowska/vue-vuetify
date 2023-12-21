<template>
  <v-container>
    <h2> Reviews</h2>
  <v-banner
    lines="three"
    class="my-4"
  >
     <v-avatar size="50" class="mx-4">
    <v-img src="https://i.pinimg.com/originals/77/71/68/7771683223d86b237a3304d6f32828b9.jpg"></v-img>
  </v-avatar>

    <v-banner-text x-small>
      What a stunning dresses. I am really pleased with the service as well!
    </v-banner-text>
    <div>
          <v-rating
            v-model="rating"
            color="yellow"
            background-color="grey"
            empty-icon="$ratingFull"
            hover
            medium
          ></v-rating>
        </div>


    

  </v-banner>
  

</v-container>
</template>
<script>

export default {
  data: () => ({
  rating: 5,

  }),
  name: 'FeedbackReview',
components: {
  
}
}


</script>
<style>
</style>