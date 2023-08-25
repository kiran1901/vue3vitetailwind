<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="w-full bg-[#725E8E] h-[60px]">
    The Footerrrrr
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
