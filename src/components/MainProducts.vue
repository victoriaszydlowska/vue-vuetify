<template>
  <v-app>
    <v-toolbar flat color="transparent">
      <v-spacer></v-spacer>
      <v-btn-toggle v-model="toggle_exclusive" group color="#49D9A0">
        <v-btn>
          <v-icon>mdi-chevron-left</v-icon>
        </v-btn>
        <v-btn>
          <v-icon>mdi-chevron-right</v-icon>
        </v-btn>
      </v-btn-toggle>
    </v-toolbar>
    <v-row justify="center" class="space px-16">
      <v-col
        cols="12"
        xs="10"
        sm="6"
        md="4"
        v-for="(product, i) in products"
        :key="i"
      >
        <v-card
          class="mx-auto rounded-xl"
          max-width="300"
          color=""
          flat
          outlined
        >
          <div align="center" justify="center">
            <v-img class="" max-height="300" max-width="300" :src="product.img">
            </v-img>
          </div>

          <v-card-title class="">{{ product.title }}</v-card-title>
          <v-card-title class="grey--text text-grey-darken-1 caption mt-n6">{{
            product.subtitle
          }}</v-card-title>
          <v-card-title class="mt-n4">{{ product.price }}</v-card-title>

          <v-card-actions class="mx-2 mt-n4">
            <strong class="mx-2 my-4" v-text="bpm"></strong>

            <v-spacer></v-spacer>
            <v-btn class="mx-2 mt-n1" fab dark small color="#FFF0EE">
              <v-icon x-small color="#FF6D59" @click="increment"
                >far fa-heart</v-icon
              >
            </v-btn>
            <v-btn class="mx-2 mt-n1" fab dark small color="#FFF0EE">
              <v-icon small color="#FF6D59">mdi-basket</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-app>
</template>

<script>
export default {
  data: () => ({
      bpm: 1,
    products: [
      { img: "https://i1.wp.com/papiliobridal.com/wp-content/uploads/2018/09/m1b-1.jpg?fit=1500%2C2000&ssl=1 ", title: "No 1", subtitle: "dreamy, detailed, modest", price: "$1100" },
      { img: "https://cdn0.hitched.co.uk/articles/images/1/6/3/4/img_84361/older-bride-wedding-dresses-prpnovias.jpg", title: "No 2", subtitle: "classy, modest, chic", price: "$1050" },
      { img: "https://i.pinimg.com/originals/fb/66/af/fb66af080ac25cecfcc00952774a6653.jpg", title: "No 3", subtitle: "feminine, beauty, style", price: "$970" },
      { img: "https://i.pinimg.com/originals/c8/e1/02/c8e102b34164383bafc4c7d9250fabcb.jpg", title: "No 4", subtitle: "simplicity, elegance, romance", price: "$1000" },
      { img: "https://www.praisewedding.com/wp-content/uploads/2019/07/12-J-Sposa-Wedding-www.jsposa.co_.kr_.jpg", title: "No 5", subtitle: "vintage, decorative, feminine", price: "$1200" },
      { img: "https://th.bing.com/th/id/OIP.x82iKg5BnoPMrK9G8ZJS5QHaLH?pid=ImgDet&w=474&h=711&rs=1", title: "No 6", subtitle: "simple, decorative, popular", price: "$1000" },
    ],
  }),
   methods: {
      decrement () {
        this.bpm--
      },
      increment () {
        this.bpm++
      },

    },
};
</script>

<style></style>
