<template>
  <div class="features">
    <v-container class="fill-height">
      <v-responsive class="d-flex align-center text-start fill-height">
        <v-row class="mb-12 mt-12">
          <v-col cols="4" class="d-none d-sm-block">

            <div class="phone"></div>
          </v-col>
          <v-col>
            <v-row class="mb-16">
              <v-col>
                <p class="text-h6 text-md-h4 text-lg-h2 font-weight-black text-center">
                  Do this and so much more
                </p>
              </v-col>
            </v-row>

            <v-row>
              <v-col class="v-col-12 v-col-sm-6 mb-16">
                <v-row>
                  <v-col cols="4">
                    <v-container
                      class="circle d-flex justify-center align-center"
                    >
                      <v-icon
                        icon="fas fa-map-pin"
                        size="x-large"
                        color="#fff"
                      />
                    </v-container>
                  </v-col>
                  <v-col cols="8" class="d-flex flex-column">
                    <v-row>
                      <p class="text-h5 mb-2">Discover POI</p>
                    </v-row>
                    <v-row>
                      <p class="">
                        Discover point of interests in new locations. Meet like
                        minds in familiar spaces. Be home away from home.
                      </p>
                    </v-row>
                  </v-col>
                </v-row>
              </v-col>

              <v-col class="v-col-12 v-col-sm-6 mb-16">
                <v-row>
                  <v-col cols="4">
                    <v-container
                      class="circle d-flex justify-center align-center"
                    >
                      <v-icon icon="fas fa-map" size="x-large" color="#fff" />
                    </v-container>
                  </v-col>
                  <v-col cols="8" class="d-flex flex-column">
                    <v-row>
                      <p class="text-h5 mb-2">Manage Locations</p>
                    </v-row>
                    <v-row>
                      <p class="">
                        Save locations, Share location updates and follow your
                        favorite locations's events using Gringo.
                      </p>
                    </v-row>
                  </v-col>
                </v-row>
              </v-col>

              <v-responsive width="100%"></v-responsive>

              <v-col class="v-col-12 v-col-sm-6">
                <v-row>
                  <v-col cols="4">
                    <v-container
                      class="circle d-flex justify-center align-center"
                    >
                      <v-icon
                        icon="fas fa-location-arrow"
                        size="x-large"
                        color="#fff"
                      />
                    </v-container>
                  </v-col>
                  <v-col cols="8" class="d-flex flex-column">
                    <v-row>
                      <p class="text-h5 mb-2">Track Assets</p>
                    </v-row>
                    <v-row>
                      <p class="">
                        See the real time location of your tracked assets from
                        our Missa tracking platform right inside Gringo.
                      </p>
                    </v-row>
                  </v-col>
                </v-row>
              </v-col>

              <v-col class="v-col-12 v-col-sm-6">
                <v-row>
                  <v-col cols="4">
                    <v-container
                      class="circle d-flex justify-center align-center"
                    >
                      <v-icon
                        icon="fas fa-shopping-bag"
                        size="x-large"
                        color="#fff"
                      />
                    </v-container>
                  </v-col>
                  <v-col cols="8" class="d-flex flex-column">
                    <v-row>
                      <p class="text-h5 mb-2">Get Deliveries</p>
                    </v-row>
                    <v-row>
                      <p class="">
                        Your favorite brands use Gringo for deliveries. Receive
                        your shopping in the right place
                        at the right time.
                      </p>
                    </v-row>
                  </v-col>
                </v-row>
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
.features {
}

.phone {
  width: 17vw;
  height: 35vw;
  background: rgb(251, 251, 251);
  border-radius: 30px;
  box-shadow: inset 0 0px 10px rgb(0 0 0 / 15%);
}
.circle {
  width: 8vh;
  height: 8vh;
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
</style>
