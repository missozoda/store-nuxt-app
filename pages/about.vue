<template>
  <div>
    <h2>About</h2>
    <p><span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Autem praesentium accusamus ex modi,
      voluptates aspernatur sequi quis tenetur reprehenderit rem!</span><span>Quod iste placeat, dignissimos aspernatur quia, animi quibusdam sunt aut at corrupti alias veniam optio deleniti ullam nulla vel? Delectus?</span></p>
      <div>
        {{ data }}
      </div>
  </div>
</template>

<script setup>
  const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p{
  margin: 20px 0;
}
</style>