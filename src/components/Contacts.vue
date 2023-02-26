<template>
  <div class="contacts">
    <v-container class="fill-height">
      <v-responsive class="d-flex align-center text-start fill-height">
        <v-row class="mb-6 d-flex align-center justify-center">
          <v-col class="v-col-12 v-col-sm-6">
            <p class="text-h6 text-md-h4 text-lg-h2 font-weight-black text-start">
              Say hello to the Gringo team
            </p>
          </v-col>
          <v-col class="v-col-12 v-col-sm-6">
            <v-row justify="space-around">
              <v-btn class="ma-2" color="purple" icon="mdi:mdi-facebook" size="large"></v-btn>
              <v-btn class="ma-2" color="purple" icon="mdi:mdi-twitter" size="large"></v-btn>
              <v-btn class="ma-2" color="purple" icon="mdi:mdi-instagram" size="large"></v-btn>
              <v-btn class="ma-2" color="purple" icon="mdi:mdi-whatsapp" size="large"></v-btn>
              <v-btn class="ma-2" color="purple" icon="mdi:mdi-youtube" size="large"></v-btn>
              <v-btn class="ma-2" color="purple" icon="mdi:mdi-email" size="large"></v-btn>
            </v-row>
          </v-col>
        </v-row>
      </v-responsive>
    </v-container>
  </div>
</template>

<script lang="ts" setup></script>

<style>
.contacts {
  height: 50vh;
  background-color: rgba(120, 221, 255, 0.419);
}
</style>
