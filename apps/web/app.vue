<script setup lang="ts">
import { Page } from "ui";

const config = useRuntimeConfig()
const { appName } = config.public

useHead({
  title: "Create Turborepo (vue-nuxt:web)",
  meta: [{ name: "description", content: "Generated by create turbo" }],
});
</script>

<template>
  <Page :app-name="appName" />
</template>
