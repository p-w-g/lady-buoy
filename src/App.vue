<script setup lang="ts">
import { RouterView } from 'vue-router'
import Burger from './assets/Burger.vue'
import { ref } from 'vue'
const show_mobile_drawer = ref(false)
const toggleDrawer = () => (show_mobile_drawer.value = !show_mobile_drawer.value)
</script>
<template>
  <v-app>
    <v-app-bar app dark>
      <v-toolbar-title class="ml-3">Lazy Buoy</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn v-show="$vuetify.display.xs" @click="toggleDrawer">
        <Burger />
      </v-btn>
      <div v-if="!$vuetify.display.xs">
        <v-btn link to="/">Home</v-btn>
        <v-btn link to="/about">Om båten</v-btn>
        <v-btn link to="/book">Att boka</v-btn>
        <v-btn link to="/contact">Kontakta oss</v-btn>
      </div>
    </v-app-bar>

    <v-navigation-drawer v-model="show_mobile_drawer" app temporary>
      <v-list-item link to="/" title="Home" />
      <v-list-item link to="/about" title="Om båten" />
      <v-list-item link to="/book" title="Att boka" />
      <v-list-item link to="/contact" title="Kontakta oss" />
    </v-navigation-drawer>

    <v-main>
      <RouterView />
    </v-main>
  </v-app>
</template>
