<template>
  <v-container fluid class="hero-container">
    <v-row align="center">
      <v-col cols="12">
        <div class="text-right">
          <h1 class="display-2">Yachtsea</h1>
          <p class="subtitle-1">En välvärdat Bavaria 36 Holiday</p>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>
<style scoped>
.hero-container {
  @media (min-width: 700px) {
    background-size: 50% 100%;
  }

  width: 100%;
  height: 20rem;
  padding: 50px;
  background-image: url('../assets/boat2.jpg');
  object-fit: contain;
}
</style>
