<template>
  <h3>
    {{ name }}您好，歡迎回來
  </h3>
  <button type="button">
    <NuxtLink :to="'/user/' + name+'/orders'">訂單頁</NuxtLink>
  </button>
</template>

<script setup>
const route = useRoute();
const name = route.params.userId;
console.log(route);

</script>