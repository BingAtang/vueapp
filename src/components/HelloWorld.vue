<script setup lang="ts">
import { ref } from '@vue/runtime-dom';
const msg = ref('');
</script>

<template>
  <div class="container">
    <h2>{{ msg }}</h2>
    <input type="text" v-model="msg" placeholder="edit it" />
  </div>
</template>

<style scoped></style>
