

<script setup>

import { ref } from 'vue'

const show = ref(true);
const list = ref([1, 2, 3]);

</script>

<template>

        <v-container class="wishlist">
        <h1> Wish list</h1>
  <v-btn @click="show = !show">Toggle List</v-btn>
  <v-btn @click="list.push(list.length + 1)">Push Number</v-btn>
  <v-btn @click="list.pop()">Pop Number</v-btn>
  <v-btn @click="list.reverse()">Reverse List</v-btn>

  <ul v-if="show && list.length">
    <li v-for="item of list " :key="item.id" >{{ item }}</li>
  </ul>
  <p v-else-if="list.length">List is not empty, but hidden.</p>
  <p v-else>Empty list</p>
  <v-file-input
    accept="image/*"
    label="File input"
  ></v-file-input>
  <h3> Print</h3>
</v-container>
</template>
<style>
.wishlist {
  
  padding:1rem 2rem;

}</style>
