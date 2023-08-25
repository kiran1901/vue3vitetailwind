<script setup>
import TheFooter from './components/TheFooter.vue'
import TheHeader from './components/TheHeader.vue'

</script>

<template>
  <div>
    <the-header />
    <div>
      <router-view />
    </div>
    <the-footer />
  </div>
</template>

<style scoped>

</style>
