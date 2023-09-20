<template>
  <div class="mx-auto my-24 text-left flex justify-between items-center">
    <div class="max-w-[55%]">
      <h2 class="text-3xl font-medium mb-8">About Fake Store API</h2>
      <p class="text-xl my-4">Fake store rest API for your e-commerce or shopping website prototype.</p>
      <p class="text-xl my-4">fakeStoreApi is a free online REST API that you can use whenever you need Pseudo-real data for your e-commerce or shopping website without running any server-side code. It's awesome for teaching purposes, sample codes, tests, etc.</p>
    </div>
    <div class="">
      <img src="../assets/images/intro.svg" alt="Intro">
    </div>
  </div>
</template>

<script setup>
// server api orqali fetch qilish
  const { data } = await useFetch('/api/currency/GBP');
</script>

<style scoped>

</style>