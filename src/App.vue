<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>
<template>
  <v-app>
    <v-navigation-drawer>
      <v-list-item
        title="Lady Buoy"
        prepend-icon="$vuetify"
        color="success"
        subtitle="Båtens hemsida"
        link
        to="/"
      >
      </v-list-item>
      <v-divider />
      <v-list-item link to="/" title="Home" />
      <v-list-item link to="/about" title="Om båten" />
      <v-list-item link to="/book" title="Att boka" />
    </v-navigation-drawer>
    <v-main>
      <RouterView />
    </v-main>
  </v-app>
</template>
