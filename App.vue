<script setup></script>

<template>
  <h1>Test</h1>
</template>

<style lang="scss">
#app {
  z-index: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  pointer-events: none;
  background-color: $color-black;

  * {
    pointer-events: all;
  }
}
</style>
