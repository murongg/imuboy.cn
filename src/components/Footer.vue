<script setup lang="ts">
const { t } = useI18n()
</script>

<template>
  <footer class="prose prose-xs mt-5 m-auto">
    <div class="text-left text-sm opacity-75 dark:opacity-50"> {{ t('footer.copyright') }}</div>
  </footer>
</template>
