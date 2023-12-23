<script setup>
defineProps({
  text: {
    type: String,
    required: true
  }
})
</script>

<template>
  <h2 class="text-4xl font-bold">{{ text }}</h2>
</template>

<style scoped>

</style>
