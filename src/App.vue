<script setup lang="ts">
import { ref } from 'vue'

const url = ref("https://tva2.sinaimg.cn/large/007YVyKcly1h5mmf47su9j30ma0mlq7v.jpg")
const srcList = ref(["https://tva2.sinaimg.cn/large/007YVyKcly1h5mmf47su9j30ma0mlq7v.jpg"])
</script>

<template>
  <el-image
    :src="url"
    :preview-src-list="srcList"
    fit="cover"
  />
</template>

<style scoped>
.el-image {
  width: 200px;
}
</style>
