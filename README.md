# 🐍 Trilha de Estudos em Python para Engenharia de Dados

Este repositório contém um plano de estudos completo para se aprofundar em Python com foco em aplicações práticas em Engenharia de Dados.

## 🎯 Objetivo

Aprimorar habilidades em Python para construir pipelines de dados mais performáticos, testáveis, organizados e prontos para ambientes de produção, com boas práticas e uso de bibliotecas amplamente utilizadas no mercado.

---

## 📂 Estrutura do Repositório

```
.
├── README.md
├── 01_python_avancado
│   └── exemplos.py
├── 02_clean_code
│   └── estrutura_projeto/
├── 03_performance_concorrencia
│   └── paralelismo.py
├── 04_testes_debugging
│   └── testes_pytest/
├── 05_bibliotecas_engenharia_dados
│   └── pandas_polars.py
└── projeto_final_pipeline
    ├── etl_pipeline/
    ├── tests/
    └── README.md
```

---

## 📌 Etapas do Estudo

### 1. Python Avançado

- Compreensões (listas, dicionários, sets)
- Funções de ordem superior, lambda, map, filter
- Decorators e closures
- Geradores (`yield`, `next`)
- `*args`, `**kwargs`, unpacking
- Manipulação de arquivos, JSON, CSV, APIs
- Type hints e validação com `pydantic`
- Estruturas com `collections`: defaultdict, Counter, deque

### 2. Clean Code e Estrutura de Projetos

- Organização em pastas (`src`, `tests`, `configs`)
- Ambientes com `venv`, `poetry` ou `pipenv`
- `logging`, tratamento de erros e docstrings
- Princípios SOLID e responsabilidade única

### 3. Performance e Concorrência

- `multiprocessing` e `concurrent.futures`
- AsyncIO para tarefas I/O bound
- `joblib` para paralelismo simples
- Profiling com `cProfile`, `line_profiler`, `memory_profiler`
- Introdução ao **Dask** e processamento distribuído

### 4. Testes e Debugging

- Testes unitários com **pytest**
- Mocks com `unittest.mock`
- Testes de integração e coverage com `pytest-cov`
- Debug com `pdb` ou VSCode

### 5. Bibliotecas úteis para Engenharia de Dados

- **pandas** / **polars**
- **pyarrow**, **fastparquet**, **fsspec**
- **sqlalchemy**
- **click** / **typer** (CLI para pipelines)
- **Airflow**, **Luigi**, **Prefect** (orquestração)

---

## 📅 Plano de 3 Meses

| Semana | Tópico Principal |
|--------|------------------|
| 1-2 | Python avançado e boas práticas |
| 3-4 | Clean Code e estrutura de projetos |
| 5-6 | Paralelismo e profiling |
| 7-8 | Testes automatizados e debugging |
| 9-10 | Bibliotecas para engenharia de dados |
| 11-12 | Projeto final (pipeline com testes, paralelismo e CLI) |

---

## 🧪 Projeto Final

> **Objetivo:** Criar um mini pipeline de ETL com:
> - Leitura de dados de múltiplas fontes
> - Processamento paralelo ou assíncrono
> - Testes automatizados com Pytest
> - Interface de linha de comando (CLI) com Click ou Typer
> - Logging estruturado e tratamento de erros

### Sugestão de estrutura do projeto final:

```
projeto_final_pipeline/
├── etl_pipeline/
│   ├── extract.py
│   ├── transform.py
│   ├── load.py
│   └── cli.py
├── tests/
│   ├── test_extract.py
│   ├── test_transform.py
│   └── test_load.py
├── requirements.txt
└── README.md
```

---

## 📚 Referências

- [Fluent Python – Luciano Ramalho](https://www.oreilly.com/library/view/fluent-python/9781491946237/)
- [Clean Code – Robert C. Martin](https://www.goodreads.com/book/show/3735293-clean-code)
- [Documentação oficial do Pytest](https://docs.pytest.org/en/latest/)
- [Curso Python Avançado – Udemy](https://www.udemy.com/course/python-advanced/)
- [Databricks Academy](https://academy.databricks.com/)

---

Sinta-se livre para adaptar o plano conforme sua rotina ou objetivos! 🚀
