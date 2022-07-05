<script setup lang="ts">
const { t, availableLocales, locale } = useI18n()

const toggleLocales = () => {
  const locales = availableLocales
  locale.value = locales[(locales.indexOf(locale.value) + 1) % locales.length]
}
</script>

<template>
  <header mt-6 text-gray-700 dark:text-gray-200 px-15>

    <nav flex items-center justify-end>

      <a class="icon-btn mx-2" href="/projects">
        {{ t('project.title') }}
      </a>

      <RouterLink class="icon-btn mx-2" to="/" :title="t('button.home')">
        <div i-carbon-home />
      </RouterLink>

      <RouterLink class="icon-btn mx-2" to="/about" :title="t('button.about')">
        <div i-carbon-dicom-overlay />
      </RouterLink>

      <a class="icon-btn mx-2" rel="noreferrer" href="https://github.com/murongg" target="_blank" title="GitHub">
        <div i-carbon-logo-github />
      </a>

      <a class="icon-btn mx-2" :title="t('button.toggle_langs')" @click="toggleLocales()">
        <div i-carbon-language />
      </a>

      <button class="icon-btn mx-2 !outline-none" :title="t('button.toggle_dark')" @click="toggleDark()">
        <div i="carbon-sun dark:carbon-moon" />
      </button>
    </nav>
  </header>
</template>
