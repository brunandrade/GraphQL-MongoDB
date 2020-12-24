<h1 align="center">
    GraphQL API com MongoDB
</h1>

## Aplicação
A aplicação é um CRUD para o controle de usuários e posts feitos por estes usuários. O projeto foi desenvolvido utilizando GraphQL, JavaScript, MongoDB e Mongoose para comunicação com a database.

## Tecnologias

- NodeJs
- GraphQL
- Apollo-Server
- JavaScript
- MongoDB
- Mongoose


## Instruções

1. Para rodar o projeto é necessário criar uma base de dados utilizando o MongoDB e alterar a ConnectionString para a sua base criada presente no aquivo `startServer.js` dentro da pasta src.

2. Após criar a base de dados é necessário rodar o compando abaixo para instalar todas as dependências utilizadas no projeto.

### `yarn install` 

3. Para inicializar o servidor graphql com o playground é preciso utilizar o comando abaixo. A aplicação irá rodar no dominio: [http://localhost:4000/graphql](http://localhost:4000/graphql) para a realização das querys ou mutations;

### `yarn dev`

 