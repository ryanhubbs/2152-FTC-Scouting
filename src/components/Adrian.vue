<template>
  <div :id="funnies">
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/Adrian.jpg">Adrian</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/brian.png">Brian</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/savanna.png">Savanna</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/caden.png">Caden</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/stears.png">Mr. Stears</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/julien.png">Julien</a>
  </div>
</template>

<script setup lang="ts">
// Fetch logo path
//const adrian = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
//const caden = $computed(() => `${import.meta.env.BASE_URL}assets/caden.png`);
</script>

<style lang="postcss">
.funnies {
  background-image:absoluteLogoPath
}
</style>
