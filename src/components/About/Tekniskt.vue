<template>
  <v-container class="minimal-container">
    <p class="subtitle-1">Tekniskt beskrivning</p>

    <v-row no-gutters>
      <v-col cols="12" sm="6">
        <v-sheet class="minimal-sheet">
          <v-list lines="one" density="compact">
            <v-list-item>Längd 11.5m</v-list-item>
            <v-list-item>Bredd 3.7mck</v-list-item>
            <v-list-item>Djup 1.85m</v-list-item>
            <v-list-item>Höjd från vattenytan: 16.5m</v-list-item>
          </v-list>
        </v-sheet>
      </v-col>
      <v-col cols="12" sm="6">
        <v-sheet class="minimal-sheet">
          <!-- Placeholder for the picture -->
          <v-img
            src="path-to-your-image.jpg"
            alt="Picture of a boat"
            class="picture-placeholder"
          ></v-img>
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

.picture-placeholder {
  max-width: 100%;
  border-radius: 8px;
}
</style>
