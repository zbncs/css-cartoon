<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import LoadingCat from '@components/loading-cat/index.vue'
import CssDog from '@components/dog/index.vue'
import FatCat from '@components/fat-cat/index.vue'
</script>

<template>
  <div>
    <!-- <loading-cat></loading-cat> -->
    <!-- <css-dog></css-dog> -->
    <fat-cat></fat-cat>
  </div>
  
</template>

<style>
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 800px;
  background: #ffe16e;
}
</style>
