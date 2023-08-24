<template>
  <div>
    <div v-for="product in products" :key="product.id">
        <NuxtLink :to="`/products/${product.id}`"> {{ product.title }} </NuxtLink>
    </div>
  </div>
</template>

<script setup>
    //fetch the products
    const { data: products } = await useFetch('https://fakestoreapi.com/products')
</script>

<style>

</style>