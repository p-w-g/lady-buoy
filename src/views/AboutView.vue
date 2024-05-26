<script setup lang="ts">
import Tekniskt from '../components/About/Tekniskt.vue'
import Utrustning from '../components/About/Utrustning.vue'
</script>

<template>
  <v-container class="minimal-container">
    <v-row no-gutters>
      <v-col cols="12" sm="6">
        <h2 class="text-h2">Om båten</h2>
      </v-col>
    </v-row>
  </v-container>
  <Tekniskt />
  <Utrustning />
</template>

<style scoped>
.minimal-container {
  padding-top: 24px;
  padding-bottom: 24px;
  background-color: #f5f5f5; /* Light grey background for contrast */
}
</style>
