# API de Alunos

API desenvolvida com FastAPI para gerenciamento de alunos e suas notas.

## 🚀 Funcionalidades

- Criar aluno com notas
- Listar alunos
- Buscar aluno por ID
- Deletar aluno
- Relacionamento entre alunos e notas

## 🛠️ Tecnologias

- FastAPI
- SQLite
- SQLAlchemy
- Pydantic

## ▶️ Como rodar o projeto

```bash
uvicorn app:app --reload

Exemplo de uso:

{
  "nome": "João",
  "notas": [7, 8, 9]
}

Listar alunos
GET /alunos

Objetivo:
Projeto criado para estudo e também para uso prático no gerenciamento de alunos.