<template>
  <div>123</div>
  <div>{{a}}</div>
  <button @click="addA">click</button>
</template>

<script setup>
ref: a = 0
const addA = () => a += 1
</script>