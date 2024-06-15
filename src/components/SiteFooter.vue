<template>
  <footer>
    <div class="footer-content">
      <a href="https://github.com/bruno-sclima" target="_blank">
        <font-awesome-icon :icon="['fab', 'github']" /> GitHub
      </a>
      <a href="https://www.linkedin.com/in/bruno-silveira-956689205/" target="_blank">
        <font-awesome-icon :icon="['fab', 'linkedin']" /> LinkedIn
      </a>
      <a href="mailto:brunobhsclima@gmail.com" target="_blank">
        <font-awesome-icon :icon="['fas', 'envelope']" /> Gmail
      </a>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter'
};
</script>

<style scoped>
footer {
  background-color: #3b5998;
  color: white;
  padding: 20px;
  width: 100%;
  text-align: center;
}
.footer-content {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
.footer-content a {
  color: white;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 5px;
}
.footer-content a:hover {
  text-decoration: underline;
}
</style>
