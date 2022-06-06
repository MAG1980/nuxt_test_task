<template>
  <ul>
    <li>
      <nuxt-link :to="{ name:'index' }">Home</nuxt-link>
    </li>
    <li>
      <nuxt-link :to="{ name:'catalog' }">Catalog</nuxt-link>
    </li>
    <li>
      <nuxt-link :to="{ name:'catalog-item-id', params:{id: 1} }">Catalog item</nuxt-link>
    </li>
    <li>
      <nuxt-link :to="{ name:'about' }">About</nuxt-link>
    </li>
    <li>
      <nuxt-link :to="{ name:'cart' }">Cart</nuxt-link>
    </li>
  </ul>
</template>

<script>
export default {
  name: "TheNavBar"
}
</script>

<style scoped>

</style>