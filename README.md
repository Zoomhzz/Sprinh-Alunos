# 🎓 API de Cadastro de Alunos

Sistema backend desenvolvido para facilitar o registro e a consulta de estudantes. Este projeto foi criado para colocar em prática conceitos de arquitetura MVC, persistência de dados e construção de APIs REST.

## 🚀 Tecnologias Utilizadas

* **Java 17** (ou a versão que você estiver usando)
* **Spring Boot 3**
* **Spring Data JPA** (Persistência)
* **MySQL** (Banco de dados)
* **Maven** (Gerenciador de dependências)
* **Insomnia/Postman** (Testes de API)

## 🛠️ Funcionalidades

- [x] **Cadastro de Alunos:** Envio de dados como Nome, R.A, E-mail e Telefone.
- [x] **Listagem:** Retorno de todos os alunos registrados no banco de dados.
- [x] **Persistência Relacional:** Integração completa com banco de dados MySQL Workbench.

## 📋 Como testar

1. Clone o repositório.
2. Configure o seu `application.properties` com as credenciais do seu MySQL local.
3. Execute a aplicação via sua IDE (VS Code/IntelliJ/Eclipse).
4. Use o Insomnia para realizar as chamadas:

### Exemplo de POST (`/Alunos`)
```json
{
  "nome": "Rodrigo",
  "r_a": "12345",
  "email": "rodrigo@email.com",
  "telefone": "71 99999-9999"
}
