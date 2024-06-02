<script setup lang="ts">
import SubHero from './components/SubHero.vue'
import Hero from './components/Hero.vue'
import Footer from './components/Footer.vue'

import AboutView from './views/AboutView.vue'
import BookingView from './views/BookingView.vue'
</script>
<template>
  <v-app>
    <v-main>
      <Hero />
      <SubHero />
      <AboutView />
      <BookingView />
    </v-main>
    <Footer />
  </v-app>
</template>
