# ☕ Java Backend Stack — Tecnologias e Utilitários

Curadoria das ferramentas essenciais para desenvolvimento backend moderno com Java e Spring Boot.

---

## 🌱 Frameworks Principais
- [Spring Framework](https://spring.io/projects/spring-framework) – Framework central para desenvolvimento modular em Java
- [Spring Boot](https://spring.io/projects/spring-boot) – Abstração que facilita a criação de aplicações Spring com configuração mínima
- [Spring Web](https://docs.spring.io/spring-boot/docs/current/reference/html/web.html) – Criação de APIs RESTful com facilidade

---

## 🛠️ Persistência de Dados
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa) – Abstração de acesso a dados sobre o JPA
- [Hibernate ORM](https://hibernate.org/orm/) – Implementação de JPA amplamente usada
- [Flyway](https://flywaydb.org/) – Versionamento e migração de banco de dados
- [Liquibase](https://www.liquibase.org/) – Alternativa robusta ao Flyway para controle de schema

---

## 📦 Dependência e Build
- [Maven](https://maven.apache.org/) – Gerenciador de dependências XML-based
- [Gradle](https://gradle.org/) – Alternativa moderna e performática com build script Groovy/Kotlin

---

## 🔐 Segurança
- [Spring Security](https://spring.io/projects/spring-security) – Segurança com autenticação, autorização e integração JWT
- [JWT (jjwt)](https://github.com/jwtk/jjwt) – Geração e verificação de tokens JWT
- [BCrypt (Spring Security)] – Hash seguro de senhas com sal

---

## 🧪 Testes
- [JUnit 5](https://junit.org/junit5/) – Framework de testes unitários
- [Mockito](https://site.mockito.org/) – Mock de dependências para testes isolados
- [Testcontainers](https://www.testcontainers.org/) – Testes com bancos de dados reais em containers Docker

---

## 📄 Documentação de APIs
- [SpringDoc OpenAPI (Swagger)](https://springdoc.org/) – Integração automática de documentação Swagger com Spring Boot 3+
- [Swagger UI](https://swagger.io/tools/swagger-ui/) – Interface visual para testar endpoints da API
- [Redoc](https://github.com/Redocly/redoc) – Visualizador alternativo baseado em OpenAPI

---

## 🧰 Utilitários Comuns
- [Lombok](https://projectlombok.org/) – Redução de boilerplate com anotações (`@Getter`, `@Builder`, etc.)
- [MapStruct](https://mapstruct.org/) – Gerador de mapeamentos DTO ↔ entidade em tempo de compilação
- [ModelMapper](http://modelmapper.org/) – Alternativa para conversão automática entre objetos

---

## 📈 Monitoramento & Logs
- [Actuator](https://docs.spring.io/spring-boot/docs/current/actuator-api/htmlsingle/) – Endpoints de health check, métricas e ambiente
- [Logback](http://logback.qos.ch/) – Logger default do Spring Boot
- [SLF4J](http://www.slf4j.org/) – Abstração de log para múltiplas implementações

---

## ☁️ Deploy e Infraestrutura
- [Docker](https://www.docker.com/) – Containerização da aplicação Spring Boot
- [Spring Boot Docker Layered JARs](https://docs.spring.io/spring-boot/docs/current/reference/html/container-images.html) – Otimização da imagem Docker
- [Heroku](https://www.heroku.com/) / [Railway](https://railway.app/) – Hosting fácil para aplicações Spring

---