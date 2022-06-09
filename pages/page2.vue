<template>
  <div>
    <h1>Page 2</h1>
     <nuxt-link to="./">page1</nuxt-link>
  </div>
</template>
<script setup>
definePageMeta({
  pageTransition: { name: "page", mode: "out-in" },
});
</script>