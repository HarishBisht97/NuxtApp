<script setup>
const route = useRoute();
console.log(route.params.id);
</script>

<template>
  <div>Events Id : {{ $route.params.id }}</div>
</template>
