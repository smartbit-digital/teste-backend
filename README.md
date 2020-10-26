# Teste BackEnd SmartBit

Olá dev! Esse é o teste usado por nós aqui da SmartBit para avaliar nossos candidatos. Estamos sempre em busca de profissionais interessados em aprender e se desenvolver.

Esse teste nós aplicamos para todos nossos candidatos, desde os Júniores até os Sêniores, mudando somente nosso critério de avaliação. Você também não é obrigado a fazer o mesmo completamente, iremos avaliar até onde você foi.

##  Desafio

Seu objetivo aqui é fazer uma API para um treinador Pokemon. As seguintes entidades devem existir:

#### Treinador

- ID
- Username
- Senha
- Pokemons

#### Pokemon

- ID
- Nome
- Peso
- Tipos

Crie as rotas/resolvers de CRUD de treinador e de Pokemons por Treinador, além da inserção/remoção de um Pokemon por treinador. A inserção de um pokemon em um treinador deve ser da seguinte Forma:

A inserção deve receber o ID do treinador e o exato nome do pokemon, a partir do nome do pokemon, procurar o mesmo na PokéAPI e inserir o ID, Peso e Tipos vindo de lá, além claro, do nome.

Após esses fluxos, criar também uma forma de autenticação para o treinador e uma rota/resolver para pegar o usuário autenticado e retornar os dados.

## Regras

- Deve ser feito em Node
- Deve ser usado um banco de dados relacional

## Diferencias

- Utilizar Typescript
- Utilizar Nest.JS
- Utilizar Graphql
- Utilizar Typeorm

## Instruções

- Inicie um repositório, caso seja privado, convide danilomartinelli429@gmail.com como maintainer;
- Mande um email para stephanie.rocha@smartbit.digital com o assunto: Teste Back-End e no corpo, seu nome completo e o link para o repositório.
