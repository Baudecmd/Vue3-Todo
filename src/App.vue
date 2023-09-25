
<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/HeaderComponent.vue'
</script>

<template>
  <div class="flex flex-col">
    <div>
      <HeaderComponent></HeaderComponent>
    </div>

    <div class="grow">
      <RouterView />
    </div>

  </div>
</template>

