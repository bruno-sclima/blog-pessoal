<template>
  <header>
    <nav>
      <ul>
        <li><router-link to="/">Blog</router-link></li>
        <li><router-link to="/about">Sobre</router-link></li>
        <li><router-link to="/description">Descrição</router-link></li>
      </ul>
    </nav>
    <div class="header-content">
      <div class="image-content">
        <img src="@/assets/profile.png" alt="Profile Picture" class="profile-pic" />
      </div>
      <div class="text-content">
        <h1>Bruno Silveira Cerqueira Lima</h1>
        <p>
          Engenheiro de software especializado em desenvolvimento backend no ecossistema Java Spring Boot, e estudante de arquitetura de software distribuídos 
        </p>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'SiteHeader'
};
</script>

<style scoped>
header {
  background-color: #3b5998;
  color: white;
  padding: 20px;
}
nav ul {
  display: flex;
  justify-content: center;
  list-style-type: none;
  padding: 0;
  margin: 0;
}
nav li {
  margin: 0 15px;
}
nav a {
  color: white;
  text-decoration: none;
}
.header-content {
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: left;
  max-width: 1200px;
  margin: 0 auto;
}
.image-content {
  margin-right: 20px;
}
.profile-pic {
  border-radius: 50%;
  width: 150px;
  height: 150px;
}
.text-content {
  max-width: 600px;
}
@media (max-width: 768px) {
  .header-content {
    flex-direction: column;
    text-align: center;
  }
  .image-content {
    margin-right: 0;
    margin-bottom: 20px;
  }
  .profile-pic {
    width: 100px;
    height: 100px;
  }
  .text-content {
    max-width: 100%;
  }
}
</style>
