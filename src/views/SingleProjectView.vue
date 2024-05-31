<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
</script>

<template>
  <h1>Project {{ route.params.id || 'default' }}</h1>
</template>
