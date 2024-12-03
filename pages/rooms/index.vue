<template>
  <h1>
    客房列表
  </h1>
  <div style="border: 1px solid red;">
    客房{{ number }}
    <button type="button">
      <NuxtLink :to="'/rooms/' + number">房型詳細頁</NuxtLink>
    </button>
  </div>

  <div style="border: 1px solid red;">
    客房{{ number1 }}
    <button type="button">
      <NuxtLink :to="'/rooms/' + number1">房型詳細頁</NuxtLink>
    </button>
  </div>
</template>

<script setup>
const number = Math.floor(Math.random() * 100) + 1;
const number1 = Math.floor(Math.random() * 100) + 1;
</script>