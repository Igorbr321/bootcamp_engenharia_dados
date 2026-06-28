# Bootcamp Engenharia de Dados

Projeto desenvolvido durante um bootcamp de Engenharia de Dados com foco na construção de um pipeline de dados completo, aplicando conceitos utilizados em ambientes corporativos.

O objetivo deste repositório é consolidar conhecimentos em ingestão, transformação, modelagem e disponibilização de dados, utilizando ferramentas amplamente adotadas no mercado.

---

## Objetivos

- Construir um pipeline de dados de ponta a ponta.
- Aplicar boas práticas de Engenharia de Dados.
- Desenvolver processos de ETL/ELT.
- Modelar dados para análise.
- Automatizar execuções de pipelines.
- Versionar todo o projeto utilizando Git.

---

## Tecnologias

- Python
- SQL
- PostgreSQL
- Apache Airflow
- Snowflake
- dbt
- Docker
- Git

---

## Arquitetura do Pipeline

```text
Fonte de Dados
      │
      ▼
PostgreSQL
      │
      ▼
Apache Airflow
      │
      ▼
Snowflake (Raw)
      │
      ▼
dbt
      │
      ▼
Camada Analítica
```

---

## Estrutura do Projeto

```text
.
├── airflow/
│   ├── dags/
│   └── plugins/
│
├── dbt/
│   ├── models/
│   ├── tests/
│   ├── macros/
│   └── snapshots/
│
├── sql/
│
├── scripts/
│
├── docker/
│
├── requirements.txt
└── README.md
```

---

## Fluxo de Dados

1. Extração dos dados da origem.
2. Orquestração do pipeline utilizando Apache Airflow.
3. Carregamento dos dados para o Snowflake.
4. Transformações utilizando dbt.
5. Disponibilização dos dados na camada analítica.

---

## Conceitos Aplicados

### Engenharia de Dados

- ETL
- ELT
- Data Pipeline
- Data Warehouse
- Orquestração de Dados
- Modelagem Analítica

### SQL

- CTEs
- Views
- Joins
- Window Functions
- Agregações
- Queries Analíticas

### Apache Airflow

- DAGs
- Tasks
- Scheduling
- Dependências entre processos

### Snowflake

- Databases
- Schemas
- Warehouses
- Stages
- Tabelas

### dbt

- Models
- Sources
- Tests
- Materializations
- Documentação

---

## Aprendizados

Durante o desenvolvimento deste projeto foram praticados:

- Construção de pipelines de dados.
- Orquestração de processos.
- Transformação de dados utilizando SQL e dbt.
- Organização em camadas de dados.
- Versionamento com Git.
- Estruturação de projetos de Engenharia de Dados.

---

## Objetivo deste Repositório

Este projeto faz parte da minha jornada de evolução como Engenheiro de Dados. O foco não é apenas reproduzir o conteúdo do bootcamp, mas compreender cada etapa do pipeline, documentar as decisões técnicas e manter um histórico da evolução dos conhecimentos adquiridos ao longo do desenvolvimento.

---
