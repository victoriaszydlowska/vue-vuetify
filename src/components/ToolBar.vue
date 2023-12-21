<template> 
    <v-toolbar flat color="rgba(0,0,0,0)" class="my-9">
         <v-btn
           icon
           light
           class="d-lg-none d-xl-flex"
         >
           <v-icon>mdi-menu</v-icon>
         </v-btn>
         <v-spacer></v-spacer>
         <v-text-field
           label="Search "
           class="pt-5 d-none d-sm-flex"
           light
           filled
           prepend-inner-icon="mdi-magnify"
           solo
           flat
           background-color="transparent"
           rounded
           outlined
         ></v-text-field>
            <v-btn
                    
                       rounded
                       flat
                       xl-large
                       class="py-7 p-2 d-none d-sm-none d-md-flex grey darken-1 white--text"
                     >
                       search
                     </v-btn>
         <v-spacer></v-spacer>
         <v-btn light flat class="mr-2">
           <v-icon left>fas fa-filter</v-icon>
           Filter
         </v-btn>
         <v-btn light flat class="mr-2">
           <v-icon left>fas fa-heart</v-icon>
           Saved
         </v-btn>
       </v-toolbar>
 </template>
 <script>
 export default {
 
 }
 </script>
 <style>
 </style>