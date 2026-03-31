# Books API | ASP.NET Core + MongoDB

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

<p align="justify">
API REST para gerenciamento de livros, desenvolvida em C# com ASP.NET Core e integrada ao MongoDB. O projeto implementa operações completas de CRUD (Create, Read, Update e Delete), seguindo o padrão de Controllers (MVC) para organização da aplicação.

Foi construída com foco na prática de desenvolvimento backend, abordando conceitos como estruturação de APIs, manipulação de dados em banco NoSQL e boas práticas de organização de código.
</p>

---

## 🛠️ Tecnologias

- C#
- ASP.NET Core
- MongoDB
- Swagger

---

## 🚀 Funcionalidades

- Cadastro de livros com os seguintes campos:
  - Nome
  - Preço
  - Categoria
  - Autor

- Operações completas de CRUD:
  - Criar livros
  - Listar todos os livros
  - Buscar livro por ID
  - Atualizar dados
  - Remover livros

---

## 🔗 Endpoints

| Método | Rota              | Descrição                     |
|--------|-------------------|--------------------------------|
| GET    | /api/books        | Lista todos os livros         |
| GET    | /api/books/{id}   | Busca um livro por ID         |
| POST   | /api/books        | Cria um novo livro            |
| PUT    | /api/books/{id}   | Atualiza os dados do livro    |
| DELETE | /api/books/{id}   | Remove um livro               |

---

## 📦 Estrutura do Projeto

- Controllers
- Models
- Services
- Configurations

---

## 📄 Exemplo de Livro (JSON)

```json
{
  "bookName": "Clean Code",
  "price": 99.90,
  "category": "Programação",
  "autor": "Robert C. Martin"
}
```

## Como Executar

1. Clone o repositório:  
   ```bash
   git clone <URL_DO_REPOSITORIO>
2. Abra a solução no Visual Studio
3. Configure a string de conexão com o MongoDB no arquivo appsettings.json (caso necessário)
4. Execute o projeto
5. Acesse o Swagger em:
   ```bash
   https://localhost:<porta>/swagger

## Testes
Os endpoints foram testados utilizando o Swagger, permitindo a validação de todas as operações de CRUD de forma prática e interativa.

## Aprendizado
Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

- Criação de APIs REST com ASP.NET Core
- Integração com banco de dados NoSQL (MongoDB)
- Estruturação utilizando padrão MVC (Controllers)
- Implementação de operações CRUD
- Organização e boas práticas no backend
