<script setup>
import {RouterView} from "vue-router";
import QuizesView from "@/views/QuizesView.vue";
</script>
<template>
  <div class="container">
    <RouterView/>


  </div>
</template>

<style scoped>
.container {
  max-width: 10000px;
  margin-top: auto;
  padding: 0 120px;
}
</style>