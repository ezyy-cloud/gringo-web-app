<template>
  <div class="footer">
    <v-container class="fill-height">
      <v-responsive class="d-flex align-center text-start fill-height">
        <v-row class="mb-6" no-gutters>
          <v-col class="d-flex v-col-12 v-col-sm-6 v-col-md-2 justify-center mt-12 mb-12">
          <v-col class="d-flex v-col-4 v-col-sm-3 v-col-md-10" ><v-img :src="Logo" /></v-col>
          </v-col>
          <v-col class="v-col-12 v-col-sm-6 v-col-md-3 text-center mt-12 mb-12">
            <p class="text-h5 font-weight-black mb-12">Quick Links</p>
            <p class="text-h6 font-weight-light">Features</p>
            <p class="text-h6 font-weight-light">Services</p>
            <p class="text-h6 font-weight-light">Downloads</p>
            <p class="text-h6 font-weight-light">Reviews</p>
          </v-col>
          <v-col class="v-col-12 v-col-sm-6 v-col-md-3 text-center mt-12 mb-12">
            <p class="text-h5 font-weight-black mb-12">Support</p>
            <p class="text-h6 font-weight-light">Report a bug</p>
            <p class="text-h6 font-weight-light">Privacy Policy</p>
            <p class="text-h6 font-weight-light">Terms and Conditions</p>
            <p class="text-h6 font-weight-light">FAQs</p>
          </v-col>
          <v-col class="v-col-12 v-col-sm-6 v-col-md-3 text-center mt-12 mb-12">
            <p class="text-h5 font-weight-black mb-12">Newsletter</p>
            <p class="text-h6 font-weight-light mb-6">
              Receive latest updates and information about the platform:
            </p>
            <v-text-field
              density="compact"
              variant="solo"
              label="Enter email"
              append-inner-icon="mdi:mdi-send"
              single-line
              hide-details
              @click:append-inner="() => {}"
            ></v-text-field>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col class="w-100 h-100 d-flex align-center justify-space-between">
            <!-- 👉 Footer: left content -->
            <span class="d-flex align-center">
              Another
              <a
                href="https://ezyy.cloud"
                target="_blank"
                rel="noopener noreferrer"
                class=" ms-1 me-1"
                >Ezyy </a>
                 Cloud
            </span>
            <!-- 👉 Footer: right content -->
            <span class="d-md-flex gap-x-4">
              {{ new Date().getFullYear() }}
              &copy;
            </span>
          </v-col>
        </v-row>
      </v-responsive>
    </v-container>
  </div>
</template>

<script lang="ts" setup>
import Logo from '@/assets/logo.svg'
</script>

<style>
.footer {
}
</style>
