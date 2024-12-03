<template>
  <h3>預約{{ route.params.roomId }}號房型頁</h3>
  <button type="button">
    <NuxtLink :to="'/rooms/' + route.params.roomId">上一步</NuxtLink>
  </button>
  <button type="button">
    <NuxtLink :to="'/booking/' + route.params.roomId">下一步</NuxtLink>
  </button>
</template>

<script setup>
const route = useRoute();
console.log(route);

</script>