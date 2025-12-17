# API Alunos

## Descrição

API Escolar para gerenciamento de alunos, cursos e matriculas. O sistema foi desenvolvido com Node + Typescript, ExpressJS, Sequelize e base de dados em PostgreSQL. Ele funciona por CLI (Command Line Interface), mas pode ser testado/utilizado por Swagger UI que está integrado no projeto.
  
## Técnologias

<div style="display: inline_block">
    <br>
    <img align="center" alt="Typescript" height="100" width="25%" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" />
    <img align="center" alt="NodeJS" height="100" width="25%" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original-wordmark.svg" />
    <img align="center" alt="Swagger UI" height="100" width="25%" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/swagger/swagger-original-wordmark.svg" />
    <img align="center" alt="PostgreSQL" height="100" width="25%" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original-wordmark.svg" />
</div>

## Como Instalar?

É possível instalar o projeto de duas formas:

- Utilizando somente Docker e utilizando o docker-compose (mais simples)
- Utilizando NodeJS e um banco de dados PostgreSQL

A baixo vou explicar como utilizar ambos

### Instalação com Docker

1. É necessário ter Docker instalado em seu computador. Siga as instruções do site oficial: [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)
2. Depois de instalar teste se está instalado corretamento utilizando o terminal (Linux/MacOS) ou PowerPoint:

  ```bash
  docker --version
  ```

3. Abra o terminal no diretorio do projeto (dentro da pasta api-alunos) e rode o seguinte comando:

  ```bash
  docker compose up -d
  ``` 

4. Apos isso o projeto estara funcional e rodando! Pode visualizar e testar a API na rota: [http://localhost:3000/api-docs](http://localhost:3000/api-docs)

5. (Opcional) Caso deseje parar o projeto, siga o comando abaixo da mesma forma no passo 3:

  ```bash
  docker compose stop 
  ``` 
  
### Instalação com NodeJS e PostgreSQL

1. É necessário para rodar dessa forma

  - NodeJS ([https://nodejs.org/pt/download](https://nodejs.org/pt/download)) [O projeto foi criado na versão 24.12]
  - PostgreSQL ([https://www.postgresql.org/download/](https://www.postgresql.org/download/)) [O projeto foi criado na versão 15]

2. (Opcional) É possível instalar um banco de dados PostgreSQL com Docker, caso instale utilize o comando a baixo para rodar:

  ```bash
  docker run --name escola \
  -e POSTGRES_USER=escola \
  -e POSTGRES_PASSWORD=escola \
  -p 5432:5432 \
  -d postgres:15
  ```

3. Após configurar o banco de dados PostgreSQL, crie um banco de dados escola (banco padrão) ou poder criar o banco com o nome e senha que achar adequado. Recomendo configurar os dados necessários para o projeto criando um arquivo .env (o arquivo .example.env defini as variaveis de ambientes já configuradas no projeto)

4. Entre dentro da pasta do projeto e rode o seguinte comando:

  ```bash
  npm i && node ./src/server.ts
  ```

5. Apos isso o projeto estara funcional e rodando! Pode visualizar e testar a API na rota: [http://localhost:3000/api-docs](http://localhost:3000/api-docs)
