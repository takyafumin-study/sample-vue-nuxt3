<template>
  <div>
    <slot name="header" />
    <Navbar />
    <slot />
  </div>
</template>

<script setup>
  import Navbar from '@/components/Nav/Navbar';
</script>

