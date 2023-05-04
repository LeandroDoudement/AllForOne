
# MySQL All for One

Esse repositório contém um projeto prático desenvolvido durante o curso de Desenvolvimento de Software da [Trybe](https://www.betrybe.com/). O objetivo do projeto é aplicar conceitos de modelagem e manipulação de dados em um ambiente de banco de dados relacional utilizando MySQL.

## Descrição Geral

O MySQL All for One é um sistema de gerenciamento de eventos, onde é possível criar e gerenciar eventos e realizar inscrições nos mesmos. O sistema possui um banco de dados relacional com múltiplas tabelas, onde são armazenados os dados de eventos, usuários e inscrições.

## Funcionalidades

O MySQL All for One possui as seguintes funcionalidades:

- Cadastro de usuários
- Autenticação de usuários
- Listagem de eventos
- Busca de eventos por nome ou descrição
- Criação de eventos
- Edição de eventos
- Remoção de eventos
- Listagem de participantes de um evento
- Criação de inscrições em eventos
- Cancelamento de inscrições em eventos

## Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [Node.js](https://nodejs.org)
- [Express](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)
- [Sequelize](https://sequelize.org/)
- [JWT](https://jwt.io/)
- [Mocha](https://mochajs.org/) e [Chai](https://www.chaijs.com/) para testes automatizados
- [Swagger](https://swagger.io/) para documentação da API

<details>
  <summary><strong>🗒️ Instruções para restaurar o banco de dados `Northwind`</strong></summary><br />

1. Faça o download do arquivo de backup [aqui](northwind.sql) clicando em "Raw", depois clicando com botão direito e selecionando "Salvar como" para salvar o arquivo em seu computador.
2. Abra o arquivo com algum editor de texto e selecione todo o conteúdo do arquivo usando `CTRL-A`.
3. Abra o MySQL Workbench.
4. Abra uma nova janela de query e cole dentro dela todo o conteúdo do arquivo `northwind.sql`.
5. Selecione todo o código com o atalho `CTRL-A` e depois clique no ícone de raio para executar a query.
6. Aguarde alguns segundos (espere em torno de 30 segundos antes de tentar fazer algo).
7. Clique no botão apontado na imagem a seguir para atualizar a listagem de banco de dados.
8. Verifique se o banco restaurado possui todas as seguintes tabelas:
9. Clique com botão direito em cada tabela e selecione "Select Rows" e certifique-se que todas as tabelas possuem registros. Caso tenha alguma faltando, faça o passo a seguir. Caso contrário, pode ir para próxima seção.
10. Caso existam tabelas faltando, drope o banco de dados clicando com o botão direito em cima do banco de dados northwind e selecionando "Drop Schema" e refaça os passos novamente, dessa vez aguardando um tempo maior quando executar o script de restauração.
</details>
