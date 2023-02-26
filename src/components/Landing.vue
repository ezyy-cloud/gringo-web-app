<template>
  <div class="landing">
  <v-container class="fill-height">
    <v-responsive class="d-flex align-center text-start fill-height">
      <v-row class="mb-6 d-flex justify-space-between">
        <v-col>
          <v-row>
            <v-col>
              <p class="text-h2 text-lg-h1 font-weight-black mb-4">
                Gringo
              </p>
              <p class="text-h4 text-lg-h3 font-weight-medium">
                Your location's potential unleashed
              </p>
            </v-col>
          </v-row>
          <v-row>
            <v-col class="v-col-12 v-col-md-12 text-h6 font-weight-regular">
              <p>
                Gringo is your personal location manager bringing the physical
                world around you at your fingertips. It brings all the Ezyy Cloud Platform
                services into one application to give you control of the world around you.
              </p>
            </v-col>
          </v-row>
          <v-row class="d-flex justify-space-between">
            <v-col class="d-flex flex-column v-col-md-6 v-col-6">
              <v-img
                :src="PlayStore"
                alt=""
              />

              <v-spacer></v-spacer>

              <v-img
                :src="AppStore"
                alt=""
              />
            </v-col>
            <v-col class="v-col-md-4 v-col-4 d-flex justify-end">
              <v-img
                src="https://ps.w.org/doqrcode/assets/icon-256x256.png?rev=2143781"
                alt=""
              />
            </v-col>
          </v-row>
        </v-col>

        <v-col class="d-none d-sm-flex justify-end align-center">
          <div class="circle d-flex justify-center align-center">
            <div class="phone"></div>
          </div>
        </v-col>
      </v-row>
    </v-responsive>
  </v-container></div>
</template>

<script lang="ts" setup>
import PlayStore from "../assets/playstore.png";
import AppStore from "../assets/appstore.png";
</script>

<style>
.landing {
  height: 100vh;
  background-color: rgba(120, 221, 255, 0.419);
}
.circle {
  width: 30vw;
  height: 30vw;
  background: linear-gradient(
    to bottom right,
    #04dff1 30%,
    #499dee 50%,
    #b02bef 80%
  );
  background-size: contain;
  background-repeat: no-repeat;
  border-radius: 50%;
}
.phone {
  width: 17vw;
  height: 35vw;
  background: rgb(251, 251, 251);
  border-radius: 30px;
  box-shadow: inset 0 0px 10px rgb(0 0 0 / 15%);
}
</style>
