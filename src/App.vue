<script setup lang="ts">
useHead({
  meta: [
    { property: 'og:title', content: 'Bruce Yu' },
    { name: 'description', content: 'Bruce Yu\'s Portfolio' },
    { name: 'twitter:card', content: 'summary' },
    // { name: 'twitter:creator', content: '@antfu7' },
  ],
})
</script>

<template>
  <NavBar />
  <main class="px-7 py-10">
    <router-view />
    <Footer />
  </main>
</template>
