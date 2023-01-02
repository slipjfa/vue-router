<script setup>
  import { RouterLink } from "vue-router";
  import { ref } from "vue"
  const randomState = ref("");
</script>

<template>
  <div>
    <RouterLink active-class="active" to="/">Home</RouterLink>
    <RouterLink active-class="active" to="/about">About</RouterLink>
    <button @click="randomState = (randomState === '') ? 'hello' : ''">Click me</button>
  {{ randomState }}
  </div>
</template>

<style>
.active {
  font-weight: 900;
  color: rgb(153, 104, 14)
}
</style>