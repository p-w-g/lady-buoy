<script setup lang="ts">
import TextBlock from '../components/TextBlock.vue'
</script>

<template>
  <v-container class="minimal-container">
    <v-row no-gutters>
      <v-col cols="12" sm="6">
        <h2 class="text-h2">Bokning</h2>
      </v-col>
    </v-row>
  </v-container>
  <TextBlock>
    <template #header>
      <p class="subtitle-1">Pris</p>
    </template>
    <template #default>
      <v-list lines="one" density="compact">
        <v-list-item>18000kr/vecka (tom v33)</v-list-item>
        <v-list-item>14000kr/vecka (v34 framåt)</v-list-item>
        <v-list-item>Deposition : 10500kr </v-list-item>
      </v-list>
    </template>
  </TextBlock>

  <TextBlock>
    <template #header>
      <p class="subtitle-1">Vilkor</p>
    </template>
    <template #default>
      <div class="text-body-1">
        <p>Kräver nautisk kompetens.</p>
        <p>Båten försäkrat hos Svenska Sjö.</p>
        <p>Kontrakt enligt mall i länken.</p>
        <p>Rabatt vid längre uthyrning</p>
        <p>
          Återbetalas i helhet om båten lämnas tillbaka i samma skick med Deposition : 10500kr
          (Samma som självrisk - Återbetalas i helhet om båten lämnas tillbaka i samma skick med
          full tank).
        </p>
        <p>10% i handpenning för att reservera båten. Resten senast vid avhämtning.</p>
        <p>Kan teckna hyreskontraktet i förväg digitalt eller vid utlämning.</p>
        <p>
          Uthyres lördag till lördag. Exakta tider enligt överenskommelse, men som tumregel avfärd
          på eftermiddag och ankomst på förmiddag.
        </p>
        <p>Ring gärna vid funderingar.</p>
      </div>
    </template>
  </TextBlock>
</template>

<style scoped>
.minimal-container {
  padding-top: 24px;
  padding-bottom: 24px;
  background-color: #f5f5f5; /* Light grey background for contrast */
}
</style>
