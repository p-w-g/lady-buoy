<template>
  <v-container class="minimal-container">
    <v-row no-gutters>
      <v-col cols="12" sm="6">
        <h2 class="text-h2" id="book">Bokning</h2>
      </v-col>
    </v-row>
  </v-container>
  <v-container class="minimal-container">
    <p class="subtitle-1">Pris och vilkor</p>
    <v-row no-gutters>
      <v-col cols="12" sm="6">
        <v-sheet class="minimal-sheet">
          <v-list lines="one" density="compact">
            <v-list-item>18000kr/vecka (tom v33)</v-list-item>
            <v-list-item>14000kr/vecka (v34 framåt)</v-list-item>
            <v-list-item>Deposition : 10500kr </v-list-item>
          </v-list>
        </v-sheet>
      </v-col>

      <v-col cols="12" sm="6">
        <v-sheet class="minimal-sheet">
          <div class="text-body-1">
            <p>Kräver nautisk kompetens. Båten försäkrat hos Svenska Sjö.</p>
            <p>Kontrakt enligt mall i länken. Rabatt vid längre uthyrning</p>
            <br />
            <p>
              Deposition: 10500kr (Samma som självrisk - Återbetalas i helhet om båten lämnas
              tillbaka i samma skick med full tank). 10% i handpenning för att reservera båten.
              Resten senast vid avhämtning.
            </p>
            <br />
            <p>
              Kan teckna hyreskontraktet i förväg digitalt eller vid utlämning. Uthyres lördag till
              lördag. Exakta tider enligt överenskommelse, men som tumregel avfärd på eftermiddag
              och ankomst på förmiddag.
            </p>
            <p>Ring gärna vid funderingar.</p>
          </div>
        </v-sheet>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.minimal-container {
  padding-top: 24px;
  padding-bottom: 24px;
  background-color: #f5f5f5;
}

.minimal-sheet {
  padding: 16px;
  margin: 16px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border: 1px solid #e0e0e0;
}
</style>
