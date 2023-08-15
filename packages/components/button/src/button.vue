<template>
  <div>我是package/components 中的 button -- {{ v }}</div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

defineOptions({
  name: 'HtButton',
});

const v = ref(0);
</script>
