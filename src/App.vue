<script setup lang="ts">
import Header from "@/components/site/Header.vue";
import router from "@/router";
import {useRoute} from "vue-router";

const routes = useRoute()
</script>

<template>
  <header v-if="routes.name !== 'Login'">
    <Header/>
  </header>
  <main>
    <RouterView/>
  </main>
</template>