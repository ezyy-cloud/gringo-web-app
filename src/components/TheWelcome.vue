<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Personal Location Manager</template>
      Manage your location on the cloud. Share real time location updates with 
      friends. Store your favorite routes and locations. Explore new locations with Gringo!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Public Transport</template>
      Get public transport on demand. With a large base of service 
      provider, getting transport to your next appointment is a breeze.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Locations</template>
      Follow your favorite locations to get latest updates on events, promotions
      and sales with Gringo. Never will you miss another event.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Deliveries</template>
      Get your favorite meals, groceries delivered right at your doorstep. We have partnered with 
      multiple restaurants and service providers to ensure you get your meal when you need it.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Tracking</template>
      Track your vehicle, assets and kids with Gringo Tracker.Gringo allows you to monitor anything 
      that matters to you right from your phone ensuring you never lose sight of what matters the most.
  </WelcomeItem>
</template>

<style>
i {
    background-color: #43D4FC !important;
  }
</style>