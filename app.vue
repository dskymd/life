<script setup lang="ts">
import { ref } from 'vue'

const count = ref(123)

const inc = () => {
  count.value++
}
</script>

<template>
  <div>{{ count }}</div>
  <button @click="inc">inc</button>
</template>
