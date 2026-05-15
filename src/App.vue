<template>
  <div class="app">
    <h1>Vercel + Vue 3 Starter</h1>
    <p>部署成功！</p>
    <button @click="count++">点击次数: {{ count }}</button>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<style>
* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: -apple-system, sans-serif; background: #f5f5f5; min-height: 100vh; display: flex; align-items: center; justify-content: center; }
.app { text-align: center; padding: 40px; background: white; border-radius: 16px; box-shadow: 0 2px 12px rgba(0,0,0,0.08); }
h1 { font-size: 24px; color: #333; margin-bottom: 12px; }
p { color: #666; margin-bottom: 24px; }
button { padding: 10px 24px; background: #222; color: white; border: none; border-radius: 8px; cursor: pointer; font-size: 16px; }
button:hover { background: #444; }
</style>
