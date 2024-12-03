<template>
  <h3>預約{{ id }}號客房-成功</h3>
  <button type="button">
    <NuxtLink :to="'/user/'+ id + '/orders'">回訂單列表</NuxtLink>
  </button>
</template>

<script setup>
const route = useRoute();
const id = route.params.bookingId;
console.log(route);

</script>