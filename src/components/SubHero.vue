<script setup lang="ts">
import TextBlock from '../components/TextBlock.vue'
</script>

<template>
  <TextBlock>
    <template #default>
      <p>
        Att segla är att uppleva friheten på ett helt unikt sätt. Känn vinden i seglen, hör vågorna
        klucka mot skrovet och njut av den orörda naturen som omger dig.
      </p>
      <br />
      <p>
        Segling är inte bara en resa, det är ett äventyr där varje dag bjuder på nya vyer och
        möjligheter. Upptäck skärgårdens gömda pärlor, ankra i lugna vikar och låt solen gå ner över
        horisonten medan du njuter av tystnaden och rofylldheten till havs.
      </p>
      <br />
      <p>
        Vår segelbåt erbjuder en oförglömlig upplevelse för både nybörjare och erfarna seglare. Kom
        och upplev magin av segling!
      </p>
    </template>
    <template #right>
      <v-col cols="12" sm="6">
        <img class="boat" src="../assets/ian-keefe-nGOK_EqQpY4-unsplash(1).jpg" alt="" srcset="" />
      </v-col>
    </template>
  </TextBlock>
</template>
<style scoped>
.boat {
  width: 100%;
  height: 230px;
  object-fit: cover;
}
</style>
