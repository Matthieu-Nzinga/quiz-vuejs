<template>
  <div>Etape {{ value + 1 }} / {{ max + 1 }}</div>
  <progress :value="value" :max="max" />
</template>
<script setup>

defineProps({
  value: Number,
  max: Number,
});
</script>
