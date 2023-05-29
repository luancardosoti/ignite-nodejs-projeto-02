# Curso Ignite Nodejs

## Projeto 02 - Criando API REST com Node.js

Nesse primeiro módulo desenvolvi uma API RESTful com Node.js,mas dessa vez utilizando o Fastify, Knex, TypeScript e outras ferramentas para auxiliar durante o desenvolvimento. Fizemos testes e2e utilizando o vitest junto com o supertest, e no final preparamos o sistema para deploy. 

# Requisitos funcionas e regras de negócios

## RF

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas as transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

## RN

- [x] A tarnsação pode ser to tipo crédito que somará ao valor total, ou débito subtrairá;
- [x] Deve ser possível identificarmos o usuário entre as requisições;
- [x] O usuário só poder visualizar transações o qual ele criou;