# ✅ API de Gerenciamento de Tarefas

API REST desenvolvida com Java e Spring Boot para gerenciamento de tarefas, seguindo uma arquitetura em camadas baseada em boas práticas de desenvolvimento backend.

O projeto implementa operações CRUD completas, persistência de dados utilizando JPA e banco de dados H2 em memória, simulando um cenário real de gerenciamento de atividades.

---

## 🎯 Objetivo

Desenvolver uma API REST para gerenciamento de tarefas aplicando conceitos fundamentais de desenvolvimento backend, incluindo:

- Arquitetura em Camadas
- APIs REST
- Persistência de Dados
- Spring Data JPA
- Boas Práticas de Desenvolvimento
- Manipulação de Entidades
- Operações CRUD

---

## 📚 Contexto

Sistemas de gerenciamento de tarefas são amplamente utilizados para organização de atividades, acompanhamento de demandas e controle operacional.

Este projeto simula uma API responsável por armazenar, consultar, atualizar e remover tarefas através de endpoints REST, permitindo integração com aplicações frontend, sistemas corporativos ou aplicações mobile.

---

## ✨ Funcionalidades

### 📌 Gestão de Tarefas

- Cadastro de tarefas
- Consulta de tarefas
- Busca por ID
- Atualização de registros
- Exclusão de tarefas

### 🔄 Operações CRUD

- Create
- Read
- Update
- Delete

### 💾 Persistência

- Banco de dados H2
- Spring Data JPA
- Mapeamento objeto-relacional (ORM)

---

## 🏗️ Arquitetura

A aplicação foi estruturada seguindo o padrão de arquitetura em camadas:

```text
Controller
    ↓
Service
    ↓
Repository
    ↓
Banco de Dados (H2)
```

---

## 📂 Estrutura do Projeto

```text
src/main/java/com/giovani/desafiotecnico
│
├── controller
│   └── TarefaController.java
│
├── model
│   └── Tarefa.java
│
├── repository
│   └── TarefaRepository.java
│
├── service
│   └── TarefaService.java
│
└── DesafioTecnicoApplication.java
```

---

## 🛠️ Tecnologias Utilizadas

### Linguagem

- Java 21

### Framework

- Spring Boot

### Persistência

- Spring Data JPA
- Hibernate

### Banco de Dados

- H2 Database

### Gerenciamento de Dependências

- Maven

### Testes de API

- Insomnia

---

## 🌐 Endpoints

### Criar Tarefa

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

---

### Listar Todas as Tarefas

```http
GET /tarefas
```

---

### Buscar Tarefa por ID

```http
GET /tarefas/{id}
```

---

### Atualizar Tarefa

```http
PUT /tarefas/{id}
```

Exemplo:

```json
{
  "titulo": "Estudar Spring Boot Avançado",
  "descricao": "Aprofundar conceitos de JPA"
}
```

---

### Excluir Tarefa

```http
DELETE /tarefas/{id}
```

---

## 🗄️ Modelo de Dados

### Tarefa

| Campo | Tipo |
|---------|---------|
| id | Long |
| titulo | String |
| descricao | String |

---

## 💡 Competências Demonstradas

- Java
- Spring Boot
- APIs REST
- Spring Data JPA
- Hibernate
- Banco de Dados Relacional
- CRUD
- Arquitetura em Camadas
- Injeção de Dependência
- Programação Orientada a Objetos
- Desenvolvimento Backend
- Maven
- Integração de Sistemas

---

## ▶️ Como Executar

### Clonar Repositório

```bash
git clone <url-do-repositorio>
```

### Executar Aplicação

```bash
./mvnw spring-boot:run
```

ou

```bash
mvn spring-boot:run
```

---

### Acessar Console H2

```text
http://localhost:8080/h2-console
```

---

## 📈 Conceitos Aplicados

- Desenvolvimento de APIs REST
- Arquitetura em Camadas
- Persistência de Dados
- ORM com JPA
- Injeção de Dependências
- Mapeamento de Entidades
- Boas Práticas Backend

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos relacionados a:

- Desenvolvimento Backend com Spring Boot;
- Criação de APIs RESTful;
- Persistência de dados com JPA;
- Arquitetura em Camadas;
- Separação de responsabilidades;
- Integração entre Controller, Service e Repository;
- Utilização de banco de dados relacional;
- Estruturação de aplicações Java para ambiente corporativo.

O projeto serviu como prática para consolidar fundamentos do ecossistema Spring, amplamente utilizado em aplicações empresariais.

---

## 👨‍💻 Autor

**Giovani Boldrini Custoias**

Projeto desenvolvido para consolidar conhecimentos em Java, Spring Boot, APIs REST e persistência de dados.

---

## 📜 Licença

Projeto desenvolvido para fins educacionais e demonstração de competências em desenvolvimento backend.
