<script setup lang="ts">
import { ref } from 'vue';

const count = ref(0);
</script>

<template>
  <div class="flex flex-col items-center justify-center h-screen gap-2">
    <h1 class="text-3xl font-bold">Welcome!</h1>
    <button class="btn" @click="count++">Count is: {{ count }}</button>
  </div>
</template>
