<template>
  <div class="description">
    <h1>Descrição</h1>
    <p>Engenheiro de software especializado em desenvolvimento backend, com experiência sólida em: microsserviços, RESTful API, Java, Spring Boot e
bancos de dados SQL e NoSQL. Certificado como Professional Cloud Developer pela Google Cloud Platform. Tenho interesse em desenvolvimento backend,
arquitetura de software e tecnologias de nuvem. Busco oportunidades desafiadoras onde possa aplicar minha expertise para impulsionar projetos e contribuir para o sucesso das organizações</p>
  </div>
</template>

<script>
export default {
  name: 'DescriptionPage'
};
</script>

<style scoped>
.description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 0 auto;
  padding: 20px;
  min-height: calc(100vh - 160px); 
   max-width: 800px;
  width: 100%;
}

.description h1,
.description p {
  margin: 10px 0;
}

@media (max-width: 768px) {
  .description {
    padding: 10px;
  }
}
</style>
