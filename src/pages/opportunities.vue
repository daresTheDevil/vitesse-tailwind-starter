<script setup lang="ts">
// import DefaultPanes from '~/components/DefaultPanes.vue'
import DefaultKanban from '~/components/DefaultKanban.vue'
const { t } = useI18n()
</script>

<template>
  <!-- <DefaultPanes /> -->
  <DefaultKanban />
</template>

<route lang="yaml">
meta:
  layout: default
</route>
