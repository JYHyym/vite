<template>
  <h1>{{ msg }}</h1>
</template>

<script setup>
const msg = 'Hello from Vue'

console.log('async evaluated')
</script>

<style scoped>
h1 {
  color: green;
}
</style>