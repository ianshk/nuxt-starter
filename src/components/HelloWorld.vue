<script setup lang="ts">
defineProps<{
  greeting: string;
}>();
</script>

<template>
  <div class="text-3xl font-bold underline">{{ greeting }}</div>
</template>
