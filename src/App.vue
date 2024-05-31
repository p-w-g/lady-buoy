<script setup lang="ts">
import SubHero from './components/SubHero.vue'
import Hero from './components/Hero.vue'
import GMap from './components/GMap.vue'

import AboutView from './views/AboutView.vue'
import BookingView from './views/BookingView.vue'
</script>
<template>
  <v-app>
    <v-main>
      <Hero />
      <SubHero />
      <GMap />
      <AboutView />
      <BookingView />
    </v-main>
  </v-app>
</template>
