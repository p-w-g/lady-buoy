<script setup lang="ts"></script>
<template>
  <v-container class="minimal-container">
    <slot name="header" />
    <v-row no-gutters>
      <!-- remember that an image still should be in v-col -->
      <slot name="left" />
      <v-col>
        <v-sheet class="minimal-sheet"><slot /></v-sheet>
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

.minimal-sheet {
  padding: 16px;
  margin: 16px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
  border: 1px solid #e0e0e0; /* Light border for definition */
}
</style>
