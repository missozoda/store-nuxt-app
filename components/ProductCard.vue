<template>
  <div class="card text-center">
    <img :src="product.image" alt="product thumb" class="thumb">
    <p class="font-bold text-grey-500 m-4 truncate">{{ product.title }}</p>
    <NuxtLink :to="`/products/${product.id}`">
      <p class="btn my-4">View details</p>
    </NuxtLink>
  </div>
</template>

<script setup>
const {product} = defineProps(['product']);
</script>

<style scoped>
.thumb {
  height: 180px;
  min-width: 70%;
  margin: 0 auto;
}
</style>