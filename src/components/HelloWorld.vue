<script setup lang="ts">
import { ref } from "vue";

interface Props {
  msg: string;
}

const props = defineProps<Props>();
</script>

<template>
  <div class="title">
    <h1>{{ props.msg }}</h1>
  </div>
</template>

<style scoped lang="scss">
.title {
  text-align: center;

  h1 {
    color: red;
  }
}
</style>
