<template>
  <NuxtLayout>
    <NuxtLoadingIndicator />
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup lang="ts">
useHead({
  htmlAttrs: { class: 'dark' }
})
</script>

<style lang="scss">
html.dark {
  background: black;
  color: white;
}
</style>