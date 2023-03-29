<template>
  <div id="adrian-container">
    <Suspense>
      <template #default>
        <Adrian />
      </template>
      <template #fallback>Loading...</template>
    </Suspense>
  </div>
</template>

<script setup lang="ts">
import Adrian from "@/components/Adrian.vue";
</script>

<style>
#adrian-container {
  display: grid;
  justify-content: center;
}
</style>
