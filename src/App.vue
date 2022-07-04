<script setup lang="ts">
useHead({
  title: 'MuRong',
  meta: [
    { name: 'description', content: `This is MuRong's blog, I share myself here.` },
    {
      name: 'theme-color',
      content: computed(() => isDark.value ? '#050505' : '#ffffff'),
    },
  ],
  link: [
    {
      rel: 'icon',
      type: 'image/svg+xml',
      href: computed(() => preferredDark.value ? '/favicon-dark.svg' : '/favicon.svg'),
    },
  ],
})
</script>

<template>
  <RouterView />
</template>
