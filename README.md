# Workshop Spring Boot com JPA
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Jp-moraiss/workshop-springboot-jpa/blob/main/LICENSE)

Este projeto é uma API RESTful desenvolvida com **Spring Boot**, **JPA/Hibernate** e **H2 Database**, como parte prática do curso de Java do professor Nélio Alves.

## 🚀 Funcionalidades

- Cadastro e gerenciamento de usuários, produtos e pedidos
- Relacionamentos entre entidades (OneToMany, ManyToMany, OneToOne)
- Criação de pagamentos e itens de pedido
- Tratamento de exceções
- Banco de dados em memória (H2) com dados de teste

## 🛠 Tecnologias

- Java 21
- Spring Boot 3  
- Spring Data JPA  
- H2 Database  
- Maven

## ▶️ Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/Jp-moraiss/workshop-springboot-jpa.git
   cd workshop-springboot-jpa
   ```

2. Execute a aplicação:

   ```bash
   ./mvnw spring-boot:run
   ```

3. Acesse: `http://localhost:8080`

## 📬 Endpoints principais

- `GET /users`
- `GET /orders`
- `GET /products`

## 🧪 Testes

Recomenda-se o uso do Postman para testar os endpoints da API.

---

Feito com 💻 por [Jp-moraiss](https://github.com/Jp-moraiss)
