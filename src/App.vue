<script setup lang="ts">
import { RouterView } from 'vue-router'
import SideBar from '@/components/SideBar.vue'
</script>

<template>
  <div class="flex h-full">
    <SideBar />
    <!-- <div class="flex-grow">
      <RouterView />
    </div> -->
  </div>
</template>

<style scoped>
html,
body {
  height: 100%;
  width: 100%;
  margin: 0;
}
</style>
