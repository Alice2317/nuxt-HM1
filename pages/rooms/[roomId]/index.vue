<template>
  <h3>
    {{ route.params.roomId }}號-客房詳細頁
  </h3>
  <button type="button">
    <NuxtLink :to="'/rooms/' + route.params.roomId + '/booking'">預約</NuxtLink>
  </button>
</template>
<script setup>
const route = useRoute();
</script>