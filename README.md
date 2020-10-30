# Banco-de-Dados - MongoDB

>*Aline Pereira* :blush:

![Banco de dados](https://st2.depositphotos.com/1845839/5603/v/950/depositphotos_56034591-stock-illustration-word-cloud-database-security.jpg)



## O que são banco de dados?

>O banco de dados é a organização e armazenagem de informações sobre um domínio específico. De forma mais simples, é o agrupamento de dados que tratam do mesmo assunto, e que precisam ser armazenados para segurança ou conferência futura. 


## Banco de dados relacional x Não relacional

Bancos de dados relacionais como MySQL, PostgreSQL e SQLite3 representam e armazenam dados em tabelas e filas. Eles são baseados em um ramo da teoria do conjunto algébrico conhecido como álgebra relacional. Bancos de dados não-relacionais como o MongoDB representam dados em coleções de documentos JSON.

### Entidades x Atributos

**Entidade** – É um objecto que existe e é distinguível de outros objectos, tem algum significado, e sobre o qual é necessário guardar informação.

**Atributos** – É uma função que mapeia um conjunto de entidades num domínio e identifica, qualifica e descreve esse conjunto de entidades. Uma entidade é representada por um conjunto de atributos.

## Exemplos de Banco de dados

- Oracle
- SQL Server
- MySQL
- PostgreSQL
- DB2
- NoSQL
- MongoDB
- Redis

## Vamos falar sobre MongoDB

O MongoDB é um dos maiores destaques do mercado. Esse banco de dados é Open Source e é um dos mais utilizados por diversas empresas. Seu sistema gira em Windows, Linux e OSX, com linguagem de programação C++.

Seu uso é orientado para documentos em JSON, permitindo que tabelas e colunas sejam criadas previamente. A performance do sistema é excelente, devido à sua linguagem de programação, o que promete melhor desempenho e tranquilidade no dia a dia.

O MongoDB foi criado para garantir uma certa dinâmica. Por isso, foi pensado em Big Data, sendo capaz de suportar seu escalonamento tanto vertical quanto horizontal. Além disso, usa replica sets, que permitem que ele seja capaz de lidar com um grande volume de informações.

abrir dois terminais: Mongod e o outro só moongo


### Alguns Comandos:

- Para criar um banco de dados ou mudar para uma que já existe:
`use Nomedobanco`

- listar todos os bancos de dados:
`show databases`

- Remover banco de dados atual:
`db.dropDatabase()`

- Criar uma Collection:
`db.createCollection(< Nome da Collection >)`

- Listar todas as collections: 
`show collections`

- Buscar todos os registros de uma collection:
`db.< NomedaCollection >.find()`

- Mostra o banco atual:
`db.current`

- busca todos os registros de uma collection:
`db.< Nomedacollection>.find()`

- Tras todos os registros de uma forma mais amigavel:
`db.< NomedaCollection>.find().pretty()`

- Retorna apenas um unico registro:
`db.< NomedaCollection>.findOne()`

- Inclui um registro dentro de uma colletion:
`db.< nomedacollection>.insertOne({< Atributo>})`

- Inclui varios registros de uma vez:
`db.db.< nomedacollection>.insertMany([{ //Objetos a serem inseridos//}])`





    