<template>
  <div class="home">
    <h2>Últimas do blog</h2>
    <BlogList />
  </div>
</template>

<script>
import BlogList from '../components/BlogList.vue';

export default {
  name: 'HomePage',
  components: {
    BlogList
  }
};
</script>

<style scoped>
.home {
  margin: 20px;
}

@media (max-width: 768px) {
  .home h2 {
    font-size: 24px;
  }
}
</style>
