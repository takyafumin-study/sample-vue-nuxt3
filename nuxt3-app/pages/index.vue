<script lang="ts" setup></script>

<template>
  <div>
    <NuxtLayout name="default">
      <template #header>ヘッダー</template>
      <h1>Main Page</h1>
      <button @click="handleClick">Coupon Get</button>
      <LazyCoupon v-if="show" />
    </NuxtLayout>
  </div>
</template>

<script setup>
  definePageMeta({
    layout:false
  });

  const show = ref(false);
  const handleClick = () => {
    show.value = true;
  };
</script>

<style scoped>
  @import '@/assets/css/index.css';
</style>
