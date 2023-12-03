<script lang="ts" setup></script>

<template>
  <div>
    <NuxtLayout name="default">
      <template #header>ヘッダー</template>
      <h1>Main Page</h1>
      <a href="/about">about</a><br>
      <a href="/custom">custom</a><br>
      <a href="/page-switch">page-switch</a><br>
    </NuxtLayout>
  </div>
</template>

<script setup>
  definePageMeta({
    layout:false
  })
</script>
