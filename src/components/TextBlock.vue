<script setup lang="ts"></script>
<template>
  <v-container class="minimal-container">
    <slot name="header" />
    <v-row no-gutters>
      <!-- remember that an image still should be in v-col -->
      <slot name="left" />
      <v-col>
        <slot />
      </v-col>
      <slot name="right" />
    </v-row>
  </v-container>
</template>

<style scoped>
.minimal-container {
  padding-top: 24px;
  padding-bottom: 24px;
  background-color: #f5f5f5; /* Light grey background for contrast */
}
</style>
