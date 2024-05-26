<template>
  <v-container class="minimal-container">
    <v-row no-gutters>
      <v-col cols="12" sm="6">
        <v-sheet class="minimal-sheet">
          <!-- Google Maps Embed -->
          <iframe
            src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=Svinninge%20Marina%20AB&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
            width="100%"
            height="450"
            style="border: 0"
            allowfullscreen="false"
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          />
        </v-sheet>
      </v-col>
      <v-col cols="12" sm="6">
        <v-sheet class="minimal-sheet">
          <!-- Text Content -->
          <v-list lines="one" density="compact">
            <v-list-item>
              Båtens placering på Google Maps:
              <v-btn
                text
                href="https://www.google.com/maps/place/Svinninge+Marina+AB/@59.4375201,18.0560766,10z/data=!4m6!3m5!1s0x465f85870ec81e6b:0x5508fd51ea5c6bff!8m2!3d59.4572983!4d18.2776362!16s%2Fg%2F1hc2_q_yr?authuser=0&entry=ttu"
                target="_blank"
              >
                Open in Google Maps
              </v-btn>
            </v-list-item>
            <v-list-item> Tveka inte att kontakta mig vid frågor. </v-list-item>
          </v-list>
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
