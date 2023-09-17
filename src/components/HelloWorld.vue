<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <h1>Jenkins</h1>
  <h1>Docker</h1>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
