<script setup>
import { RouterView } from 'vue-router'
import { Button } from '@packages/ui-lib'

import { Button as AButton } from 'ant-design-vue'
</script>

<template>
  <Button>share Button 123</Button>
  <a-button class="bg-blue-500 border-blue-500 text-white">Antd Button</a-button>
  <p class="text-white p-4 m-4 underline text-lg">in this project test</p>
  <RouterView />
</template>

<style scoped></style>
