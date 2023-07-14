<script setup lang="ts" generic="T">
const props = defineProps<{
  data: T
  name: string
}>()
</script>

<template>
  <div>{{ props.name }}</div>
</template>
