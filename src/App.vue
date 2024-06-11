<script setup lang="ts">
import Hero from './components/HeroComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

import AboutView from './views/AboutView.vue'
import BookingView from './views/BookingView.vue'
import WharfView from './views/WharfView.vue'
import AvailabilityView from './views/AvailabilityView.vue'
import ToCView from './views/ToCView.vue'
</script>

<template>
  <v-app>
    <Hero />
    <br />
    <v-main class="d-flex align-center justify-center">
      <v-container>
        <v-row class="d-flex align-center justify-center">
          <v-col cols="12" sm="8" md="12">
            <AboutView />
            <AvailabilityView />
            <WharfView />
            <ToCView />
            <BookingView />
          </v-col>
        </v-row>
      </v-container>
    </v-main>
    <FooterComponent />
  </v-app>
</template>
