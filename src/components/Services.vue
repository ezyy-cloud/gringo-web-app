<template>
  <div class="services">
    <v-container class="fill-height">
      <v-responsive class="d-flex align-center text-start fill-height">
        <v-row class="mb-12 mt-12">
          <v-col>
            <p class="text-h6 text-md-h4 text-lg-h2 font-weight-black text-center">
              Grow your business with Gringo
            </p>
          </v-col>
        </v-row>
        <v-row class="mb-6">
          <v-col class="v-col-12 v-col-sm-4">
            <v-hover v-slot="{ isHovering, props }" open-delay="10">
              <v-card
                class="rounded-s-xl"
                :elevation="isHovering ? 4 : 0"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-col class="d-flex flex-column justify-center align-center">
                  <v-container
                    class="circleB d-flex justify-center align-center mt-16 mb-12"
                  >
                    <v-icon
                      icon="mdi:mdi-advertisements"
                      size="x-large"
                      color="#fff"
                    ></v-icon>
                  </v-container>
                  <v-card-item>
                    <v-card-title>Advertise your location</v-card-title>
                  </v-card-item>

                  <v-card-text class="text-center">
                    Advertise your location on Gringo. Be visible to customers
                    nearby who are interested in your business. Drive
                    physical traffic to your location. Get on your customer's
                    screen just in time for them to visit you.
                  </v-card-text>
                </v-col>
              </v-card>
            </v-hover>
          </v-col>

          <v-col class="v-col-12 v-col-sm-4">
            <v-hover v-slot="{ isHovering, props }" open-delay="10">
              <v-card
                class="rounded-0"
                :elevation="isHovering ? 4 : 0"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-col class="d-flex flex-column justify-center align-center">
                  <v-container
                    class="circleA d-flex justify-center align-center mt-16 mb-12"
                  >
                    <v-icon
                      icon="mdi:mdi-car-connected"
                      size="x-large"
                      color="#fff"
                    ></v-icon>
                  </v-container>
                  <v-card-item>
                    <v-card-title>Public Transport</v-card-title>
                  </v-card-item>

                  <v-card-text class="text-center">
                    Move Gringo customers between locations. Join the growing
                    network of public transport providers who are on the
                    platform. Focus on managing your vehicle fleet and let us
                    worry about getting you the customers.
                  </v-card-text>
                </v-col>
              </v-card>
            </v-hover>
          </v-col>

          <v-col class="v-col-12 v-col-sm-4">
            <v-hover v-slot="{ isHovering, props }" open-delay="10">
              <v-card
                class="rounded-e-xl"
                :elevation="isHovering ? 4 : 0"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-col class="d-flex flex-column justify-center align-center">
                  <v-container
                    class="circleC d-flex justify-center align-center mt-16 mb-12"
                  >
                    <v-icon
                      icon="mdi:mdi-truck-delivery"
                      size="x-large"
                      color="#fff"
                    ></v-icon>
                  </v-container>
                  <v-card-item>
                    <v-card-title>On Demand Services</v-card-title>
                  </v-card-item>

                  <v-card-text class="text-center">
                    Build your on-demand services on top of Gringo. Let us worry
                    about the piping and plumbing required to orchestrate
                    deliveries to your customers. Focus on product quality and
                    leave the dirty work to us.
                  </v-card-text>
                </v-col>
              </v-card>
            </v-hover>
          </v-col>
        </v-row>
      </v-responsive>
    </v-container>
  </div>
</template>

<script lang="ts" setup></script>

<style scoped>
.services {
  background-color: rgba(120, 221, 255, 0.419);
}

.circleA {
  width: 12vh;
  height: 12vh;
  background: #b02bef;
  background-size: contain;
  background-repeat: no-repeat;
  border-radius: 50%;
}
.circleB {
  width: 12vh;
  height: 12vh;
  background: #499dee;
  background-size: contain;
  background-repeat: no-repeat;
  border-radius: 50%;
}
.circleC {
  width: 12vh;
  height: 12vh;
  background: #04dff1 30%;
  background-size: contain;
  background-repeat: no-repeat;
  border-radius: 50%;
}
</style>
