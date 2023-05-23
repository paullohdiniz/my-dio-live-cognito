# Minha atividade prática do DIO Live Coding do dia 22/05/2023

## Serviços AWS utilizados

- Amazon Cognito
- Amazon DynamoDB
- Amazon API Gateway
- AWS Lambda

## 01 DEV

### API REST no Amazon API Gateway
* Feito
- Resources -> Actions -> Create Resource -> Resource Name [Items] -> Create Resource

### No Amazon DynamoDB

* Feito
- DynamoDB Dashboard -> Tables -> Create table -> Table name [Items] -> Partition key [id] -> Create table

### No AWS Lambda

#### Função para inserir item

* Feito
- Add função ```put_item_function.js``` disponível na pasta ```/src``` -> Deploy
- Role
- Policy
- putItem

### Integrando o API Gateway com o Lambda backend

* Feito
- Resources Create method - POST/GET/DELETE/PATCH

### Teste POSTMAN

* Feito

### No Amazon Cognito

### No POSTMAN

* Feito
- Add request -> Authorization
- Type - OAuth 2.0

