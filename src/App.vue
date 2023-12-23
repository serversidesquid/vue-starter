<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="container mx-auto flex space-x-4 p-4">
    <img alt="Vue logo" class="logo" src="@/assets/images/logo.svg" width="32" height="32" />

    <nav class="flex space-x-2">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>

  <RouterView class="container mx-auto" />
</template>

<style scoped>
nav a {
  @apply p-2 rounded bg-gray-200;
}
nav a:hover {
  @apply bg-green-600 text-white;
}
</style>
