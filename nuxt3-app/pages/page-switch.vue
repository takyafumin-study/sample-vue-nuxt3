<template>
  <div>
    <h1>PageSwitch Page</h1>
    <button @click="enableCustomLayout">Update Layout</button>
  </div>
</template>

<script setup>
const enableCustomLayout = () => {
  setPageLayout('custom')
}
definePageMeta({
  // layout: false
})
</script>


