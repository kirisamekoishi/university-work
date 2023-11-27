<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div id="app">
    <div class="relative z-0 flex h-full w-full overflow-hidden">
      <!-- 可能会用到的左侧栏 -->
      <div>
  
      </div>
      <!-- 主页面 -->
      <div class="relative flex h-full max-w-full flex-1 flex-col overflow-hidden">
        <RouterView />
      </div>
    </div>
  </div>
</template>

<style scoped></style>
