<template>
  <h1>Item {{ id }}</h1>
</template>

<script setup>
const route = useRoute();
const id = route.params.id;
</script>

<style scoped>

</style>