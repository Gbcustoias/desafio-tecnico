# Desafio Técnico - API de Tarefas

API REST desenvolvida com Spring Boot para gerenciamento de tarefas, utilizando arquitetura em camadas (Model → Repository → Service → Controller), persistência de dados com JPA e banco de dados H2.

## Tecnologias Utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- Banco de Dados H2
- Maven
- Insomnia

## Estrutura do Projeto

```text
src/main/java/com/giovani/desafiotecnico
│
├── controller
│   └── TarefaController
│
├── model
│   └── Tarefa
│
├── repository
│   └── TarefaRepository
│
├── service
│   └── TarefaService
│
└── DesafioTecnicoApplication
```

## Funcionalidades

- Cadastrar tarefa
- Listar todas as tarefas
- Buscar tarefa por ID
- Atualizar tarefa
- Excluir tarefa

## Endpoints

### Criar tarefa

```http
POST /tarefas
```

Exemplo de requisição:

```json
{
  "titulo": "Estudar Spring Boot",
  "descricao": "Realizar desafio técnico"
}
```

### Listar tarefas

```http
GET /tarefas
```

### Buscar tarefa por ID

```http
GET /tarefas/{id}
```

