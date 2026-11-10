# API REST - Baozi Store

API REST em Java com Spring Boot, Spring Data JPA e banco H2 (relacional) para controle de clientes, produtos e pedidos de uma loja de pão chinês.

## Como rodar
1. Java 17+ e Maven instalados (ou abra o projeto no IntelliJ/Eclipse/VS Code como projeto Maven).
2. Execute a classe `BaoziStoreApplication`.
3. A API sobe em http://localhost:8080

## Endpoints
| Recurso  | POST | GET (todos) | GET /{id} | DELETE /{id} |
|----------|------|-------------|-----------|--------------|
| /clientes | ok | ok | ok | ok |
| /produtos | ok | ok | ok | ok |
| /pedidos  | ok | ok | ok | ok |

## Estrutura
`model` (entidades JPA), `repository` (Spring Data JPA) e `controller` (endpoints REST).
