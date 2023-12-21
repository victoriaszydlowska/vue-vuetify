<template>
  <v-app>
      <NavBar />
      <DrawerComponent />
    <v-container fluid class="hero">
    
      <v-card class="mx-auto rounded-xl white" flat>
  
  
                <v-card-title class="top ml-10 pt-9" v>
                  <h2 class="title1">Order it today.</h2>
                </v-card-title>
                <v-card-title class="ml-10 mt-n8">
                  <h2 class="title2">Find your perfect dress.</h2>
                </v-card-title>
                <v-card-text class="ml-10">
                  <h3 class="colored">With attention to details </h3>
                </v-card-text>
                <v-card-text class="ml-10">
                  <v-row>
                    <v-col cols="9">
                   <p> As a company, we specialise in elegant, handmade wedding dresses. We take care of every little detail to provide the best possible experience for our clients in preparation for their special day.</p>
                    </v-col>
                
                  </v-row>
                </v-card-text>
            </v-card>
    
      </v-container>
      <ToolBar />
      <AppBar />
      <MainProducts />
      <PaginationElement />
      <FeedbackReview />
      <IconSection />
  
      <FooterBar />
    
  </v-app>
  </template>
  
  <script>
    import NavBar from '../components/NavBar'
    import MainProducts from '../components/MainProducts'
    import FeedbackReview from '../components/FeedbackReview'
    import FooterBar from '../components/FooterBar'
    import PaginationElement from '../components/PaginationElement'
    import IconSection from '../components/IconSection'
    import ToolBar from '../components/ToolBar.vue'
    import AppBar from '../components/AppBar.vue'
    import DrawerComponent from '@/components/DrawerComponent.vue'
  
  
  
  
  
  
    export default {
      name: 'HomePage',
  
      components: {
      NavBar,
      FeedbackReview,
      PaginationElement,
      IconSection,
      FooterBar,
      ToolBar,
      AppBar,
      DrawerComponent,
      MainProducts
  },
    }
  </script>
  <style >
  .hero {
    background: url('https://images.squarespace-cdn.com/content/v1/56a0cf5740667abfbc331dcc/78a9d9b7-977b-4edb-a766-1d1dc749ce49/SR5613.jpg?format=1000w');
    background-size: cover;
    height: 60vh;
    padding:8vw;
    margin-bottom: 2vw;
  }
  .colored{
    color:#FF6D59;
    padding-bottom: none;
  }
  .col-9{
    padding-bottom:none !important;
    padding-top:none !important;
  
  }
  
   
  </style> 
  