

#  API de Cadastro de Usuários

Uma API REST simples e robusta para gerenciamento de usuários, construída com **Spring Boot**. Este projeto demonstra as funcionalidades essenciais de **CRUD** (Criar, Ler, Atualizar, Deletar), servindo como uma base excelente para aplicações mais complexas.

##  Funcionalidades

| Ação | Endpoint | Descrição |
| :--- | :--- | :--- |
| **Criar Usuário** | `POST /users` | Adiciona um novo usuário ao banco de dados. |
| **Consultar Usuário** | `GET /users/{email}` | Busca um usuário específico através do seu endereço de e-mail. |
| **Atualizar Usuário** | `PUT /users/{id}` | Atualiza as informações de um usuário existente, identificado pelo seu ID. |
| **Deletar Usuário** | `DELETE /users/{email}` | Remove um usuário do banco de dados utilizando seu e-mail. |

-----



