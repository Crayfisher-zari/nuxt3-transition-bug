<template>
  <div>
    <h1>Page 1</h1>
    <nuxt-link to="./page2">page2</nuxt-link>
  </div>
</template>
<script setup>
definePageMeta({
  pageTransition: { name: "page", mode: "out-in" },
});
</script>
