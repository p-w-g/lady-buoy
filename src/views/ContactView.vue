<script setup lang="ts">
import TextBlock from '../components/TextBlock.vue'
</script>
<template>
  <h2 class="text-h2">Kontakta oss</h2>
  <TextBlock>
    <template #header>
      <p class="subtitle-1">Skicka gärna ett meddelande vid funderingar</p>
    </template>
    <template #default>
      <v-list lines="one" density="compact">
        <v-list-item>Email?</v-list-item>
        <v-list-item>Telefon?</v-list-item>
      </v-list>
    </template>
  </TextBlock>
</template>
