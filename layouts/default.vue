<template>
  <header style="display: flex;justify-content: space-between;">
    <nuxt-link to="/">Logo</nuxt-link>
    <nuxt-link to="/rooms">客房旅宿頁</nuxt-link>
    <nuxt-link to="/account/login">登入頁</nuxt-link>
  </header>
  <hr/>
  <br><br>
  <slot />
  <br><br>
  <hr/>
  <footer>
    default:footer
  </footer>
</template>