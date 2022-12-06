<template>
  <div>
    test:
    {{ data.test }}
  </div>
</template>
<script setup lang="ts">
import { reactive } from 'vue'

const data = reactive({test: 'name'})
</script>

