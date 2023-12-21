<template>
  <v-app>
 
  <NavBar />
  <CarouselComponent />
  <SomeContent />
<ContactForm />
<WavyBackground />

  <FooterBar />


</v-app>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import SomeContent from '@/components/SomeContent.vue';
import FooterBar from '@/components/FooterBar.vue';
import WavyBackground from '@/components/WavyBackground.vue';
import CarouselComponent from '@/components/CarouselComponent.vue';
import ContactForm from '@/components/ContactForm.vue';

export default {
  name: 'AboutPage',

  components: {
    NavBar,
    SomeContent,
    FooterBar,
    WavyBackground,
    CarouselComponent,
    ContactForm
},
}
</script>
