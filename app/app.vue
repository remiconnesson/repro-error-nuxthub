<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

// access the `store` variable anywhere in the component ✨
const store = useCounterStore()
</script>

<template>
  <UApp>
    <NuxtPage />
  </UApp>
</template>
