<template>
  <div>123</div>
  <div>{{a}}</div>
  <button @click="addA">click</button>
</template>

<script setup>
import { ref } from 'vue'
const a = ref(0)
const addA = () => a.value += 1
</script>