<template>
  <div class="card">
    <img :src="image" alt="" class="icon">

    <h2 class="text-body">{{ title }}</h2>

    <p class="text-body is-muted">{{ description }}</p>
  </div>
</template>

<script setup>
  const { image, title, description } = defineProps({
    image: String,
    title: String,
    description: String,

  })
</script>

<style scoped>
@import "card.less";
</style>