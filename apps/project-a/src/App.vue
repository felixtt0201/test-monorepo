<script setup>
import { RouterView } from 'vue-router'
import { Button } from '@packages/ui-lib'

import { Button as AButton } from 'ant-design-vue'
</script>

<template>
  <Button>Deploy Github Page Test222</Button>
  <a-button class="bg-red-500 border-red-500 text-white">Antd Button</a-button>
  <p class="text-white p-4 m-4 underline text-lg">in this project test</p>
  <RouterView />
</template>

<style scoped></style>
