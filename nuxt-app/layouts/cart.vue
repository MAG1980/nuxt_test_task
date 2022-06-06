<template>
  <div>
    <slot />
    <NuxtLink to="/">Home</NuxtLink>
  </div>
</template>

<script>
definePageMeta({
  layout: 'cart'
})
</script>