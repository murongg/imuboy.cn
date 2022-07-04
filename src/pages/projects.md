---
title: Projects - MuRong
display: Projects
subtitle: List of projects that I am proud of
description: List of projects that I am proud of
projects:
  Vue Ecosystem:
    - name: 'Vue3 Lazylaod'
      link: 'https://github.com/murongg/vue3-lazyload'
      desc: 'A Vue3.x image lazyload plugin'
      icon: 'i-bi-images'
    - name: 'Win11 Vue'
      link: 'https://github.com/murongg/win11vue'
      desc: 'Win11 UI for Vue'
      icon: 'i-ic-twotone-desktop-windows'
    - name: 'Vue Reconstruct'
      link: 'https://github.com/murongg/vue-reconstruct'
      desc: 'Help you quickly upgrade from Vue 2.x to Vue 3.x !'
      icon: 'i-ri-tools-fill'

  Wechat Mini Program:
    - name: 'Lin UI'
      link: 'https://github.com/TaleLin/lin-ui'
      desc: '简洁、易用、灵活的微信小程序组件库'
      icon: 'i-cib-wechat'

  Image Utils:
    - name: 'image2file'
      link: 'https://github.com/murongg/image2file'
      desc: 'Simple image / svg / psd / file convert.'
      icon: 'i-mdi:image-refresh-outline'
    - name: 'imagetracer'
      link: 'https://github.com/murongg/imagetracer'
      desc: 'Simple raster image tracer and vectorizer written in TypeScript.'
      icon: 'i-carbon:svg'

  Maintaining:
    - name: 'Vagmi'
      link: 'https://github.com/wobsoriano/vagmi'
      desc: 'Vue composables for Ethereum'
      icon: 'i-mdi-ethereum'
      
  Contributed:
    - name: 'VueUse'
      link: 'https://github.com/vueuse'
      desc: 'Collection of Composition API utils for Vue 2 and 3'
      icon: 'vueuse'
    - name: 'Vitest'
      link: 'https://github.com/vitest-dev/vitest'
      desc: 'A Vite-native test framework.'
      icon: 'vitest'
      
  Configurations:
    - name: 'eslint-config'
      link: 'https://github.com/murongg/eslint-config'
      desc: 'My ESLint config presets'
      icon: 'i-simple-icons:eslint'
---

<ListProjects :projects="frontmatter.projects"/>
