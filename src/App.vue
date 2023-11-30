<template>
  <Input type="input" value="" />
  <!-- // XXX: 下面的Input组件不会报类型错误，再类型收窄工作的情况下，value值应该期望传的是一个Array<string>类型的值 -->
  <Input type="select" value="" />
</template>

<script setup lang="ts">
import Input from './components/Input.vue';
</script>
