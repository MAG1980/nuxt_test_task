<template>
<div>

  <h1>Main page</h1>

<!--  <NuxtWelcome />-->
  <NuxtPage />
</div>
</template>

<script>
import TheNavBar from "../components/TheNavBar";
export default {
  name: "index.vue",
  components: {TheNavBar},
  // layout: 'default'
}
</script>

<style scoped>

</style>