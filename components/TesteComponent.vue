<script setup lang="ts">
const props = defineProps<{
  msg: string
}>()
</script>

<template>
  <p>{{ props.msg }}</p>
</template>
