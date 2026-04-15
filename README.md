# EduTrack API

Backend desenvolvido em Python com FastAPI para gerenciamento de alunos, notas e desempenho acadêmico.

## 🚀 Funcionalidades

* ✅ Criar aluno com notas
* ✅ Listar todos os alunos
* ✅ Buscar aluno por ID
* ✅ Atualizar aluno
* ✅ Remover aluno
* ✅ Cálculo automático de média
* ✅ Status: Aprovado / Reprovado
* ✅ Relacionamento entre alunos e notas
* ✅ Documentação automática com Swagger

## 🛠️ Tecnologias

* Python
* FastAPI
* SQLAlchemy
* SQLite
* Pydantic

## 📂 Estrutura do Projeto

```text
app.py        # Configuração principal
routers.py    # Rotas da API
services.py   # Regras de negócio
alunos.db     # Banco SQLite
```

## ▶️ Como executar localmente

```bash
uvicorn app:app --reload
```

## 📘 Documentação

Acesse no navegador:

```text
http://127.0.0.1:8000/docs
```

## 📌 Exemplo de uso

### Criar aluno

```json
{
  "nome": "Sávio Cambui",
  "notas": [7.5, 8.1, 9.2, 3.9]
}
```

## 🎯 Objetivo

Projeto criado para prática de desenvolvimento backend, arquitetura de APIs e gerenciamento acadêmico.
