<script setup>
defineProps({
  type: {
    type: String,
    default: 'primary',
  },
})
</script>

<template>
  <button :class="['btn', type]">
    <slot></slot>
  </button>
</template>

<style scoped>
/* here to write tailwindcss */
.btn {
  @apply rounded bg-blue-600 px-6 py-2 text-base font-semibold text-white;
}
</style>
