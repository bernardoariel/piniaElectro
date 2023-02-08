<script setup lang="ts">
import { useCounterOptionsStore } from '@/store/conter-options';

const counter = useCounterOptionsStore();
</script>
<template>
  <h1>El valor es {{  counter.count }}</h1>
  <h4>Ultimo cambio {{ counter.lastChanged }} </h4>
</template>

<style scoped>

</style>