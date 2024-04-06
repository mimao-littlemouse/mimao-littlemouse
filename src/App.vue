<script setup lang="ts">
import Layout from './components/Layout.vue';
</script>

<template>
  <Layout>
    <template #header="{ msg  }">
      <div class="w-100 h-100 bg-info">

      </div>
    </template>
    <template #default>
      <div class="w-100 h-100 bg-danger">

      </div>
    </template>
  </Layout>
</template>

<style scoped>

</style>
