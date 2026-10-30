<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <button @click="count++" class="btn-cnt">Count is {{ count }}</button>
  <button @click="count = 0">Count Reset</button>
</template>

<style>
.btn-cnt {
  width: 100px;
  height: 100px;
  background-color: cadetblue;
}
</style>
