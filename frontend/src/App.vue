<script setup lang="ts"></script>

<template>
  <div class="background">
  </div>
</template>

<style scoped>
:global(html, body, #app) {
  margin: 0;
  padding: 0;
  height: 100%;
}

/* Clamp the gray box to the viewport */
.background {
  position: fixed;   /* pins to viewport */
  inset: 0;          /* top/right/bottom/left = 0 */
  background: #1e1e2e;
}
</style>
