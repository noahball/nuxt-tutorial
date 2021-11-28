<template>
  <div class="card">
    <img :src="require(`@/static/img/${card.image || 'fe1.jpg'}`)" alt="fe" class="image" />
  </div>
</template>

<script>
  export default {
    props: ['card']
  }

</script>

<style scoped>
  .card {
    width: 24%;
    height: 12.5rem;
    border-radius: 0.5rem;
    overflow: hidden;
    margin-bottom: 1.5rem;
    cursor: pointer;
  }

  .image {
    width: 100%;
    height: 100%
  }

</style>
