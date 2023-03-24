<script setup lang="ts">
  defineProps({
    name: {
      type: String,
      default: 'about-us',
    },
  })
</script>

<template>
  <div
    style="
      min-height: 100px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
    "
  >
    <span style="color: #0198cd">[[about-us (Vue 3.2)]]</span>
  </div>
</template>

<style scoped></style>
