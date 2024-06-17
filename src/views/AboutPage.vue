<template>
  <div class="about">
    <section>
      <h1>Experiência Profissional</h1>
      <p>
        Desenvolvedor Backend responsável pelo desenvolvimento e manutenção de RESTful API e microsserviços em projetos Java SpringBoot, com uso de bancos de dados relacionais e não relacionais como: MySQL, MongoBD, OpenSearch e Redis, construção de recursos computacionais na AWS, e confecção de testes unitários com Junit e Mockito. De modo a construir soluções eficientes e escaláveis, garantindo a entrega pontual conforme os padrões de qualidade estabelecidos e melhores práticas.
      </p>
    </section>
    <section>
      <h1>Formação</h1>
      <ul>
        <li>Bacharel em Engenharia de Software pela PUC Minas</li>
        <li>Graduando na pós-graduação de especialização em arquitetura de software distribuído</li>
        <li>Certificação: Google Cloud Certified Professional Cloud Developer - Google Cloud Plataform</li>
      </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: 'AboutPage'
};
</script>

<style scoped>
.about {
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

.about section {
  margin-bottom: 40px;
}

.about h1 {
  margin: 10px 0;
}

.about p {
  margin: 10px 0;
}

.about ul {
  list-style-type: none;
  padding: 0;
}

.about li {
  margin: 5px 0;
}

@media (max-width: 768px) {
  .about {
    padding: 10px;
  }
}
</style>
