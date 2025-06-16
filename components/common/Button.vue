<template>
  <button :class="[type || 'button-primary', 'text-body']"><slot /></button>
</template>

<script setup>
  const { type } = defineProps({
    type: String,
  })

  console.log(type)
</script>

<style scoped>
  @import "./buttons-styles.less";
</style>