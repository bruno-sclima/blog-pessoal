<template>
  <div class="blog-list">
    <BlogItem v-for="n in 3" :key="n" />
    <a href="#">Ver tudo</a>
  </div>
</template>

<script>
import BlogItem from './BlogItem.vue';

export default {
  name: 'BlogList',
  components: {
    BlogItem
  }
};
</script>

<style scoped>
.blog-list {
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}
a {
  display: block;
  margin-top: 20px;
  color: #3b5998;
}

@media (max-width: 768px) {
  a {
    font-size: 14px;
  }
}
</style>
