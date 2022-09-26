<script setup lang="ts">
import { ref } from 'vue'

const src = ref("https://tva2.sinaimg.cn/large/007YVyKcly1h5mmf47su9j30ma0mlq7v.jpg")
</script>

<template>
  <img :src="src">
</template>

<style scoped>
img {
  width: 200px;
}
</style>
