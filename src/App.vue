<script setup>
import AppHeader from './components/AppHeader.vue'
import HomePage from './pages/HomePage.vue'
</script>

<template>
<AppHeader/>
<HomePage/>
  <router-view></router-view>
</template>

<style lang="scss">
    @import '../node_modules/bootstrap/scss/bootstrap';
</style>
