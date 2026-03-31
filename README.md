# Books API - ASP.NET Core

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

<p align="justify">
API desenvolvida em <strong>ASP.NET Core (C#)</strong> utilizando o padrão de <strong>Controllers</strong>, com integração ao <strong>MongoDB</strong> (NoSQL). Este projeto foi criado como
atividade acadêmica com o objetivo de praticar a construção de uma <strong>API REST completa (CRUD)</strong>, permitindo operações de criação, leitura, atualização e exclusão de dados,
além de consolidar conhecimentos em desenvolvimento backend e integração com banco de dados não relacional.
</p>


## Funcionalidades

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
  - Deletar livros

---

## Endpoints

<div align="center">

<table>
<tr>
<th>Método</th>
<th>Rota</th>
<th>Descrição</th>
</tr>

<tr><td>GET</td><td>/api/books</td><td>Lista todos os livros</td></tr>
<tr><td>GET</td><td>/api/books/{id}</td><td>Busca um livro pelo ID</td></tr>
<tr><td>POST</td><td>/api/books</td><td>Cria um novo livro</td></tr>
<tr><td>PUT</td><td>/api/books/{id}</td><td>Atualiza todos os dados</td></tr>
<tr><td>DELETE</td><td>/api/books/{id}</td><td>Remove um livro</td></tr>

</table>

</div>

---

## Exemplo de Livro (JSON)

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
3. Configure a conexão com o MongoDB no arquivo de configuração (caso necessário)
4. Execute o projeto
5. Utilize ferramentas como Swagger para testar os endpoints

## Testes

Todos os endpoints foram testados utilizando o <strong>Swagger</strong>, garantindo o funcionamento correto das operações de CRUD.
