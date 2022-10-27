<template>
  <div
    ref="layout"
    class="layout-default"
  >
    <Navigation />

    <slot />
  </div>
</template>

<script setup lang="ts">

</script>

<style lang="scss" scoped>
.layout-default {
  --apply: w-full;
}
</style>
