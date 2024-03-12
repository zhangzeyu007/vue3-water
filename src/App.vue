<!--
 * @Description: 
 * @Author: 张泽雨
 * @Date: 2024-03-04 19:20:38
 * @LastEditors: 张泽雨
 * @LastEditTime: 2024-03-12 17:43:26
 * @FilePath: \vue3-water\src\App.vue
-->
<script setup>
import { RouterView } from "vue-router";
</script>

<template>
  <RouterView />
</template>

<style scoped lang="scss">
.nav {
  display: flex;
  .book {
    color: #000;
    background-color: #f2f2f2;
    padding: 10px;
    margin: 10px;
    display: inline-block;
  }
}
</style>
