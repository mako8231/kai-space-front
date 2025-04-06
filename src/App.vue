<script setup lang="ts">
import ForumNav from './components/ForumNav.vue';
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <ForumNav></ForumNav>
  </header>
  <RouterView />
</template>

