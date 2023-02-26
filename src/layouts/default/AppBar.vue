<template>
  <v-app-bar :flat="appBarFlat" :style="background" transition="scroll-y-transition">
    <v-app-bar-nav-icon
      variant="text"
      @click.stop="toggleDrawer()"
      class="d-sm-none"
    ></v-app-bar-nav-icon>

    <v-container class="fill-height d-none d-sm-flex align-center justify-end">
      <v-btn class="text-uppercase" v-for="link in links" :key="link.value" variant="text">
        {{ link.title }}
      </v-btn>
    </v-container>
  </v-app-bar>

  <v-navigation-drawer v-model="drawer" location="bottom" temporary>
    <v-list :items="links"></v-list>
  </v-navigation-drawer>
</template>

<script setup lang="ts">
import { ref, onMounted } from "vue";


const checkScroll = () => {
    if (document.documentElement.scrollTop > 50) {
      appBarFlat.value = false
      background.value = "background: rgba(255, 255, 255)"
    } else {
      appBarFlat.value = true
      background.value = "background: rgba(120, 221, 255, 0.419)"
    }
  };

onMounted(() => {
  window.onscroll = () => checkScroll()
});

let drawer = ref(false);

let appBarFlat = ref(true)

let background = ref("background: rgba(120, 221, 255, 0.419)")

const toggleDrawer = () => {
  drawer.value = !drawer.value;
};

const links = ref([
  {
    title: "Home",
    value: "foo",
  },
  {
    title: "Features",
    value: "bar",
  },
  {
    title: "Services",
    value: "fizz",
  },
  {
    title: "Contact",
    value: "buzz",
  },
]);
</script>
