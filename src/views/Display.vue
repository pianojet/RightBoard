<script setup lang="ts">
import Board from "../components/Board.vue";
</script>

<template>
  <main id="main-board">
    <Board />
  </main>
</template>

<style lang="scss">
@use "sass:map";
@import "@/assets/styles/colors/color-palette.scss";

#main-board {
  background-color: map.get($boardColorsLightMode, "bg");
  color: black;
  height: 100vh;
  width: 100vw;
}
</style>