<script setup lang="ts">
defineProps<{
  msg: string;
}>();
</script>

<template>
  <div class="hello">
    <span>Hello World! {{ msg }}</span>
  </div>
</template>

<style scoped></style>
