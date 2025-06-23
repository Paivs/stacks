# 🔧 Node.js Backend Stack — Tecnologias e Utilitários

Uma curadoria das melhores bibliotecas e ferramentas para construção de APIs modernas, seguras e performáticas com Node.js.

---

## 🚀 Frameworks e Servidores
- [Express](https://expressjs.com/) – Framework web rápido, flexível e minimalista
- [Fastify](https://www.fastify.io/) – Alternativa mais rápida com suporte nativo a JSON Schema

---

## 🔐 Autenticação e Segurança
- [jsonwebtoken (JWT)](https://github.com/auth0/node-jsonwebtoken) – Criação e verificação de tokens JWT
- [bcrypt](https://github.com/kelektiv/node.bcrypt.js) – Hash de senhas com salt automático
- [cors](https://github.com/expressjs/cors) – Controle de acesso por origem (CORS)
- [helmet](https://helmetjs.github.io/) – Middleware de segurança (headers HTTP)

---

## 🧠 ORM / Banco de Dados
- [Sequelize](https://sequelize.org/) – ORM para MySQL, PostgreSQL, SQLite e outros
- [sequelize-paginate](https://www.npmjs.com/package/sequelize-paginate) – Plugin de paginação fácil
- [Prisma](https://www.prisma.io/) – ORM moderno baseado em schema declarativo (alternativa ao Sequelize)
- [pg](https://node-postgres.com/) – Driver nativo PostgreSQL
- [mongoose](https://mongoosejs.com/) – ODM para MongoDB

---

## 🔄 Validação e Tipagem
- [Zod](https://zod.dev/) – Validador de esquema TypeScript-first
- [Joi](https://joi.dev/) – Validação de dados poderosa e robusta
- [Yup](https://github.com/jquense/yup) – Alternativa popular, especialmente com formulários

---

## 📦 Utilitários e Helpers
- [dotenv](https://www.npmjs.com/package/dotenv) – Carregamento de variáveis de ambiente `.env`
- [dayjs](https://day.js.org/) – Manipulação de datas moderna e leve
- [uuid](https://www.npmjs.com/package/uuid) – Geração de identificadores únicos
- [slugify](https://www.npmjs.com/package/slugify) – Geração de slugs amigáveis para URLs
- [morgan](https://www.npmjs.com/package/morgan) – Logger de requisições HTTP

---

## 🧪 Testes
- [Jest](https://jestjs.io/) – Testes unitários e integração
- [Supertest](https://github.com/ladjs/supertest) – Testes de endpoints HTTP
- [Vitest](https://vitest.dev/) – Alternativa moderna ao Jest (ideal com ESM/Vite)

---

## 🧰 Middlewares úteis para Express
- [express-async-errors](https://www.npmjs.com/package/express-async-errors) – Permite capturar erros assíncronos
- [express-rate-limit](https://www.npmjs.com/package/express-rate-limit) – Limitação de requisições
- [express-validator](https://express-validator.github.io/) – Middleware de validação com integração a Express

---

## 🧵 Uploads e Arquivos
- [multer](https://github.com/expressjs/multer) – Upload de arquivos via multipart/form-data
- [sharp](https://sharp.pixelplumbing.com/) – Manipulação de imagens no backend

---

## 🗂 Organização Avançada
- [module-alias](https://www.npmjs.com/package/module-alias) – Alias personalizados para importar com `@/` em vez de `../../`
- [tsyringe](https://github.com/microsoft/tsyringe) – Injeção de dependência para projetos TypeScript

---

## 🧪 Documentação e Testes de API
- [Swagger UI Express](https://github.com/scottie1984/swagger-ui-express) – Visualização de documentação Swagger
- [Redoc](https://github.com/Redocly/redoc) – UI moderna para OpenAPI
- [Postman](https://www.postman.com/) – Testes manuais e automáticos de APIs

---

## 🔁 Exemplos de Organização de Projeto
- `/controllers` – Lógica das rotas
- `/services` – Camada de regra de negócio
- `/models` – Definições do banco (Sequelize, Prisma, Mongoose)
- `/routes` – Arquivos de roteamento
- `/middlewares` – Autenticação, validação, erros
- `/utils` – Helpers e funções puras

---

## ✅ Sugestão de Scripts no `package.json`
```json
{
  "scripts": {
    "dev": "nodemon src/server.js",
    "start": "node src/server.js",
    "test": "jest"
  }
}
```