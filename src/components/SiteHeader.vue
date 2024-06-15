<template>
  <header>
    <div class="header-content">
      <div class="image-content">
        <img src="@/assets/profile.png" alt="Profile Picture" class="profile-pic" />
      </div>
      <div class="text-content">
        <h1>Bruno Silveira Cerqueira Lima</h1>
        <p>
          Engenheiro de software, atuando como desenvolvedor backend com uso do ecossistema Spring Boot Java, e estudante de Arquitetura de Software Distribuído.
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
  padding: 40px 20px;
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
