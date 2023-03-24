<script setup lang="ts">
  defineProps({
    name: {
      type: String,
      default: 'index',
    },
  })
</script>

<template>
  <div class="font-serif text-gray-500">
    <HeroSection /><HelpingAnimals /><GetInvolved /><DiscoverProjects /><TheFooter />
  </div>
</template>

<style scoped></style>
