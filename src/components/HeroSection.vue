<template>
  <v-container fluid class="hero-container">
    <v-row align="center">
      <v-col cols="12">
        <div class="text-right">
          <h1 class="display-2">Bavaria 36 Holiday</h1>
          <p class="subtitle-1">Tre hytt ger mycket utrymme för sällskåpet</p>
          <p class="subtitle-1">Tillgänglig från Svinninge Marina.</p>
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
  height: auto;
  padding: 50px;
  background-image: url('../assets/boat2.jpg');
  object-fit: contain;
}

.hero-btn {
  position: absolute;
  bottom: 20px;
  right: 20px;
}
</style>
