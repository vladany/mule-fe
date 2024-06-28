<script setup>
import { ref } from 'vue'

const message = ref('Hello Mary!')
</script>

<template>
  <h1>{{ message }}</h1>
</template>