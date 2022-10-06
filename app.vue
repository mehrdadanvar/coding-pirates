<template>
  <div class="app">
    <Navbar />
    <NuxtPage></NuxtPage>
  </div>
</template>
<script>
import Navbar from "./components/Navbar.vue";
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Lora&display=swap");
.app {
  font-family: "Lora", serif;
}
</style>
