<template>
  <div>
    <button @click="handleClick">Hiển thị</button>
    <button @click="handleClick2">Ẩn</button>
    <h4 v-if="isVisible">Nội dung được hiển thị</h4>
    <h4 v-else>Nội dung bị ẩn</h4>
  </div>
</template>

<script setup>
import { ref } from 'vue';
    const isVisible = ref(true);
    const handleClick = () => {
        isVisible.value = true
    }
    const handleClick2 = () => {
        isVisible.value =false
    }
</script>

<style>

</style>