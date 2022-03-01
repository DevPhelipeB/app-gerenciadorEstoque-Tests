## Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.

### ✅ Objetivo do projeto

Este projeto API REST para o gerenciamento de estoques de cerveja. tem como objetivo desenvolver testes unitários para validar o sistema de gerenciamento de estoques de cerveja, e criar testes unitários com JUnit e Mockito. Além disso, também desenvolver funcionalidades da API através da prática do TDD.

### 📺 Funcionalidades do projeto

 - Criação;
 - Listagem;
 - Consulta por nome;
 - Exclusão de cervejas;
 - TDD: incremento e decremento do número de cervejas no estoque.


### ▶ Executar o projeto

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido: 

* Java 14 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.

