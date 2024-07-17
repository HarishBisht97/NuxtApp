<script setup>
const counter = useCounter();
</script>

<template>
  <div>
    <h2>Counter : {{ counter }}</h2>
    <button @click="counter++" class="button-style">+</button>
    <button @click="counter--" class="button-style">-</button>
  </div>
</template>

<style></style>
