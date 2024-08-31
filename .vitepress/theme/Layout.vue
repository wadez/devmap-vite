<script setup lang="ts">
  import { useData } from "vitepress";

  // https://vitepress.dev/reference/runtime-api#usedata
  const { site, frontmatter } = useData();
</script>

<template>
  <nav class="flex items-center space-x-3">
    <a href="/">Home</a>
    <span>|</span>
    <a href="/pages/about">About</a>
  </nav>
  <main class="prose">
    <Content />
  </main>
</template>
