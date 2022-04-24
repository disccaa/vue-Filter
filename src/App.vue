<template>
  <div>
    <RouterLink to="/">Home</RouterLink> |
    <RouterLink to="/products">Products</RouterLink>|
    <RouterLink to="/products/:id">Product</RouterLink>|
  </div>
    <RouterView />
</template>

<script>
export default {
  name: 'App'
};
</script>

<style scoped>
</style>