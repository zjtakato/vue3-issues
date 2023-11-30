<template>
  <div>xx</div>
</template>

<script setup lang="ts">
type InputProps =
  | {
      type?: 'input';
      value: string;
    }
  | {
      type?: 'select';
      value: Array<string>;
    };

defineProps<InputProps>();
</script>
