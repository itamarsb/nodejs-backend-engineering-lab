<div align="center">

<p align="center">
    <img src="assets/Topo_repositorio_NodeJs_backend_2026, 20_39_49.png">
</p>

# 🚀 Node.js Backend Engineering Lab

### Laboratórios práticos para preparação de Desenvolvedores Backend Júnior

Repositório focado na construção de aplicações modernas utilizando **Node.js**, **TypeScript**, **NestJS**, **PostgreSQL**, **Docker**, **Jest** e **boas práticas de arquitetura**, simulando a evolução de um projeto utilizado em ambiente corporativo.

---

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)
![Node.js](https://img.shields.io/badge/Node.js-22.x-339933?logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-11.x-E0234E?logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Latest-2496ED?logo=docker&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-Testing-C21325?logo=jest&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-success)

</div>

---

## Visão Geral

```mermaid
flowchart TD

A[Fundamentos Node.js]
B[TypeScript]
C[Express]
D[NestJS]
E[PostgreSQL]
F[Docker]
G[Testes]
H[Observabilidade]
I[Projeto Final]

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
G --> H
H --> I
```

---

# 📖 Sobre o Projeto

Este repositório reúne uma sequência de laboratórios práticos desenvolvidos para preparar candidatos para vagas de **Desenvolvedor Backend Júnior**.

O objetivo não é apenas ensinar uma tecnologia específica, mas sim demonstrar como um sistema backend evolui desde sua criação até um ambiente semelhante ao encontrado em empresas de desenvolvimento de software.

Durante os laboratórios será construída uma única aplicação, que receberá novas funcionalidades e melhorias de arquitetura de forma incremental.

---

# 🎯 Objetivos

Ao concluir este repositório, o desenvolvedor terá praticado:

- Desenvolvimento Backend moderno
- Node.js
- TypeScript
- NestJS
- APIs REST
- PostgreSQL
- TypeORM
- Docker
- Testes Automatizados
- Documentação OpenAPI
- Autenticação JWT
- Logs Estruturados
- Observabilidade
- Boas práticas de Segurança
- SOLID
- Clean Architecture

---

# 🛠️ Tecnologias

| Categoria | Tecnologias |
|:------------:|-------------|
| Linguagem | Node.js, TypeScript |
| Framework | NestJS, Express |
| Banco de Dados | PostgreSQL |
| ORM | TypeORM |
| Containers | Docker |
| Testes | Jest |
| Documentação | Swagger / OpenAPI |
| Segurança | JWT, Helmet |
| Observabilidade | Pino, OpenTelemetry, Prometheus |
| Versionamento | Git e GitHub |

---

## 🗺️ Roadmap

A evolução do repositório foi organizada em laboratórios independentes, permitindo estudar cada conceito de forma incremental.

| Status | Laboratório | Objetivo | Principais Tecnologias |
|:------:|-------------|----------|------------------------|
| ⬜ | **LAB 01 — Fundamentos do Node.js** | Conhecer o runtime, npm e estrutura de projetos | Node.js, npm |
| ⬜ | **LAB 02 — Fundamentos do TypeScript** | Aprender tipagem estática e recursos modernos da linguagem | TypeScript |
| ⬜ | **LAB 03 — Primeira API com Express** | Construir uma API REST simples | Express.js |
| ⬜ | **LAB 04 — Primeira API com NestJS** | Conhecer a arquitetura do framework | NestJS |
| ⬜ | **LAB 05 — APIs REST** | Implementar boas práticas em APIs RESTful | REST, HTTP |
| ⬜ | **LAB 06 — Validação de Dados** | Validar requisições de entrada | class-validator, ValidationPipe |
| ⬜ | **LAB 07 — Autenticação com JWT** | Implementar autenticação baseada em tokens | JWT, Passport |
| ⬜ | **LAB 08 — PostgreSQL** | Integrar a aplicação com banco de dados relacional | PostgreSQL |
| ⬜ | **LAB 09 — TypeORM** | Trabalhar com ORM e persistência de dados | TypeORM |
| ⬜ | **LAB 10 — CRUD Completo** | Desenvolver operações completas de CRUD | NestJS, PostgreSQL |
| ⬜ | **LAB 11 — Paginação** | Implementar paginação e ordenação | TypeORM |
| ⬜ | **LAB 12 — Filtros e Busca** | Criar consultas avançadas | SQL, QueryBuilder |
| ⬜ | **LAB 13 — Docker** | Containerizar a aplicação | Docker |
| ⬜ | **LAB 14 — Testes Automatizados** | Escrever testes unitários e de integração | Jest |
| ⬜ | **LAB 15 — Documentação com Swagger** | Gerar documentação automática da API | Swagger / OpenAPI |
| ⬜ | **LAB 16 — Logs Estruturados** | Produzir logs profissionais | Winston, Pino |
| ⬜ | **LAB 17 — Observabilidade** | Introduzir métricas e tracing | OpenTelemetry |
| ⬜ | **LAB 18 — Tratamento Global de Erros** | Padronizar respostas de erro | Exception Filters |
| ⬜ | **LAB 19 — Deploy em Produção** | Publicar a aplicação | Docker, Nginx |
| ⬜ | **LAB 20 — Projeto Final** | Consolidar todos os conhecimentos adquiridos | Node.js, NestJS |


### Legenda

| Símbolo | Significado |
|:---------:|-------------|
| ⬜ | Não iniciado |
| 🟨 | Em desenvolvimento |
| ✅ | Concluído |


➡️ **Roadmap completo:** [roadmap.md](roadmap.md)


---

# 🏗️ Arquitetura do Repositório

```text
.
├── assets/
│   ├── banners/
│   ├── diagrams/
│   └── screenshots/
│
├── docs/
│
├── templates/
│
├── LAB 01 - Fundamentos do Node.js/
├── LAB 02 - Fundamentos do TypeScript/
├── LAB 03 - Primeira API com Express/
├── ...
├── LAB 20 - Projeto Final/
│
├── README.md
├── roadmap.md
├── CONTRIBUTING.md
├── CHANGELOG.md
├── LICENSE
└── .gitignore
```

---

# 🚗 Projeto Final

Ao longo dos laboratórios será desenvolvido um sistema completo de gestão para concessionárias de veículos.

O projeto evoluirá continuamente, simulando o desenvolvimento incremental utilizado em equipes profissionais.

## Funcionalidades

- Cadastro de Clientes
- Cadastro de Veículos
- Cadastro de Vendedores
- Propostas Comerciais
- Test Drive
- Agenda
- Ordens de Serviço
- Histórico de Atendimento
- Dashboard
- Relatórios

---

# ⭐ Diferenciais

Este repositório procura ir além dos exemplos tradicionais encontrados em cursos introdutórios.

Entre os diferenciais estão:

- Projeto único evoluindo ao longo de todos os laboratórios
- Arquitetura documentada em Mermaid
- Estrutura semelhante à utilizada em projetos corporativos
- Código organizado em camadas
- Commits organizados
- Documentação técnica detalhada
- Boas práticas de Engenharia de Software
- Observabilidade aplicada ao desenvolvimento backend

---

# 📊 Observabilidade

Um laboratório específico será dedicado à implementação de recursos normalmente encontrados em aplicações em produção.

Serão abordados:

- Logs estruturados com Pino
- Métricas com Prometheus
- Tracing distribuído com OpenTelemetry
- Health Checks
- Endpoints `/health`
- Endpoints `/metrics`

---

# 🎓 Objetivo Educacional

Este repositório faz parte de um conjunto de projetos desenvolvidos para demonstrar competências práticas em:

- Desenvolvimento Backend
- Engenharia de Software
- APIs REST
- Cloud Computing
- Observabilidade
- DevOps

---

# Competências Desenvolvidas

Ao concluir este repositório o estudante terá desenvolvido experiência prática em:

- Desenvolvimento Backend
- APIs REST
- Arquitetura em Camadas
- SOLID
- Clean Architecture
- TypeScript
- NestJS
- PostgreSQL
- Docker
- Testes Automatizados
- Swagger/OpenAPI
- JWT
- Logs Estruturados
- Observabilidade
- Deploy

---

# 🤝 Contribuições

Sugestões de melhorias, correções e novas ideias são sempre bem-vindas.

Caso identifique algum problema ou queira contribuir com o projeto, fique à vontade para abrir uma *Issue* ou enviar um *Pull Request*.

---

# 📄 Licença

Este projeto é distribuído sob a licença **MIT**.

---

## 📈 Repository Metrics

<p align="center">
    
<a href="https://info.flagcounter.com/xQCQ">
<img src="https://s01.flagcounter.com/count/xQCQ/bg_FFFFFF/txt_000000/border_CCCCCC/columns_8/maxflags_100/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>

</p>
