<template>
  <div class="screenshots">
    <v-container class="fill-height">
      <v-responsive class="d-flex align-center text-start fill-height">
        <v-row  class="mb-12 mt-12">
          <v-col cols="4" class="d-flex align-center">
            <p class="text-h6 text-md-h4 text-lg-h2 font-weight-black text-end">
                We care about your expereience using Gringo
              </p>
          </v-col>
          <v-col cols="8">
          <v-row>
            <v-col>
              <div class="phone"></div>
             </v-col>
            <v-col>
              <div class="phone"></div>
             </v-col>
            <v-col>
              <div class="phone"></div>
             </v-col>
            </v-row>
          </v-col>

        </v-row>
      </v-responsive>
    </v-container>
  </div>
</template>

<script lang="ts" setup></script>

<style scoped>
.screenshots {
  height: 100vh;
}

.phone {
  width: 16vw;
  height: 30vw;
  background: rgb(251, 251, 251);
  border-radius: 30px;
  box-shadow: inset 0 0px 10px rgb(0 0 0 / 15%);
}
</style>
