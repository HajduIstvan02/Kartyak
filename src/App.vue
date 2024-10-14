<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>

    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink> |
        <RouterLink to="/about">Táblázat</RouterLink> |
        <RouterLink to="/about">Kártyák</RouterLink> |
      </nav>
      <div>
        <RouterView/>
      </div>
    </div>


</template>

<style scoped>
</style>
