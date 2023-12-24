<script setup>
defineProps({
  text: {
    type: String,
    required: true,
  },
  icon: {
    type: String,
    required: false,
    default: null,
  },
})
</script>

<template>
  <h2 class="text-4xl font-bold">
    <font-awesome-icon v-if="icon" :icon="icon"></font-awesome-icon>
    {{ text }}
  </h2>
</template>

<style scoped></style>
