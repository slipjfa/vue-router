<script setup>
import { ref } from "vue"
  import { RouterView } from "vue-router";
  import Nav from "./components/Nav.vue";

  const randomState = ref("");
</script>

<template>

  <Nav />

  <RouterView />
  
</template>