<script setup lang="ts">
import {MyTool, Button} from "@hsf/vue-components"
import HelloWorld from "./components/HelloWorld.vue";
import "@hsf/vue-components/dist/style.css"

</script>

<template>
  <div>
    <MyTool></MyTool>
    <Button tip="hanshufei"></Button>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
