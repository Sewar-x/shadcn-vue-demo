<script setup lang="ts">
import { Button } from '@/components/ui/button'
import { Checkbox } from '@/components/ui/checkbox'
</script>

<template>
  <div class="demo-container">
    <Button>点击按钮</Button>
    <Checkbox></Checkbox>
  </div>
</template>

<style scoped>
.demo-container {
  width: 200px;
   display: flex;
   flex-direction: column;
   gap: 10px;
}
</style>
