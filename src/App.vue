<template>
  <div>
    <h1>Vue 3 + TS + Pinia Starter</h1>
    <button @click="counter.increment">Count is: {{ counter.count }}</button>
  </div>
</template>

<script setup lang="ts">
import { useCounterStore } from './stores/counter'
const counter = useCounterStore()
</script>
