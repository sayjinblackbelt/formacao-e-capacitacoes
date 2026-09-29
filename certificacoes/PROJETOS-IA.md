# Projetos de IA e arquitetura — Evidências técnicas e aplicação

Esta página detalha projetos prioritários de IA e arquitetura de soluções do portfólio e sua relação com a formação em IA, GenAI, agentes, automação, desenvolvimento, dados, streaming e educação.

> A descrição abaixo é derivada da documentação atual dos próprios repositórios. Onde o projeto ainda está em roadmap, protótipo ou preparação operacional, isso é explicitamente indicado.

## 01 · NEXA Studio

**Papel no portfólio:** ecossistema multidisciplinar que integra design, estratégia, tecnologia e comunicação visual, com experimentação tecnológica documentada.

**Competências demonstradas:** Design, comunicação visual, frontend, Node.js/API, PostgreSQL, Supabase, CI, testes, governança, QA, segurança e arquitetura de produto digital.

**Maturidade:** `4.10.3-A — HOSTING PREPARATION / IN VALIDATION`.

**Links:** [Repositório](https://github.com/sayjinblackbelt/NEXA-Studio) · [Site](https://sayjinblackbelt.github.io/NEXA-Studio/) · [NEXA Lab](https://sayjinblackbelt.github.io/NEXA-Studio/studio.html)

## 02 · Document Intelligence Agent

**Papel no portfólio:** aplicação de IA assistida e automação para análise estruturada de documentos.

**Competências demonstradas:** Python, processamento de documentos, OCR, análise determinística, IA assistida, JSON estruturado, SQLite, APIs, JWT, Docker, testes, GitHub Actions/CI, dashboards, processamento em lote, comparação documental e auditoria.

**Fluxo:** TXT/PDF/DOCX → extração de texto → análise determinística → IA Local/OpenAI/Ollama → JSON estruturado → SQLite → histórico, filtros e exportação.

**Maturidade:** projeto demonstrativo com API, interface, testes, Docker e CI documentados.

**Link:** [Repositório](https://github.com/sayjinblackbelt/document-intelligence-agent)

## 03 · Agente PMT

**Papel no portfólio:** aplicação de IA em educação, empregabilidade, aprendizagem e autonomia digital.

**Arquitetura:** três agentes especializados — Agente Carreira, Agente Estudos e Agente Administração Digital.

**Competências demonstradas:** arquitetura de agentes, IA aplicada à educação, design de experiência, tecnologia educacional, engenharia de prompts, segurança e responsabilidade em IA.

**Maturidade:** protótipo publicado no GitHub Pages; testes de integração, piloto PMT, avaliação pedagógica e versão 2.0 permanecem no roadmap.

**Links:** [Repositório](https://github.com/sayjinblackbelt/Agente-PMT) · [Demo](https://sayjinblackbelt.github.io/Agente-PMT/)

## 04 · AI Financial Agent Builder

**Papel no portfólio:** projeto que combina dados estruturados, análise determinística e arquitetura de agente.

**Competências demonstradas:** Python, Flask, SQLite, modelagem de dados, análise determinística, dashboards, API, configuração de agentes, geração de prompts, testes, GitHub Actions/CI e arquitetura local-first.

**Fluxo:** Guided Onboarding → Financial Profile → Flask API → SQLite → Financial Analyzer → Insights/Alerts/Trends → Agent Configuration → Future Conversational AI.

**Maturidade:** `MVP v0.3 — validated core / browser validation next`.

**Links:** [Repositório](https://github.com/sayjinblackbelt/AI-Financial-Agent-Builder) · [Case interativo](https://sayjinblackbelt.github.io/AI-Financial-Agent-Builder/)

## 05 · Confluent Realtime Payment Pipeline

**Papel no portfólio:** aplicação prática de arquitetura orientada a eventos e engenharia de dados em streaming, construída a partir do Bootcamp IBM Confluent — Dados em tempo real para agentes de IA.

**Arquitetura documentada:** PostgreSQL → CDC → Confluent Cloud/Kafka → Schema Registry → Flink SQL → `fraud-alerts` → Consumer.

**Competências demonstradas:** Event-Driven Architecture, Kafka, tópicos e partições, offsets, Consumer Groups, semânticas de entrega, evolução de schema, CDC, streaming, Flink SQL, joins, janelas temporais, enriquecimento de eventos e detecção de transações suspeitas.

**Regra de negócio do desafio:** três transações do mesmo cartão em uma janela de 60 segundos geram um alerta.

**Estado:** implementação estrutural preparada; execução no Confluent Cloud, evidências operacionais e custo real serão registrados após a configuração do ambiente de laboratório.

**Link:** [Repositório](https://github.com/sayjinblackbelt/confluent-realtime-payment-pipeline)

## Comparação técnica

| Projeto | IA / Agentes | Dados | Streaming | Backend | Interface | Educação | Maturidade |
|---|---|---|---|---|---|---|---|
| NEXA Studio | arquitetura/experimentação | PostgreSQL | — | Node.js API | GitHub Pages / NEXA Lab | — | Protótipo em validação |
| Document Intelligence Agent | IA assistida | SQLite | — | Python API | Web | — | Demonstrativo com CI |
| Agente PMT | 3 agentes | — | — | arquitetura de agentes | GitHub Pages | **central** | Protótipo publicado |
| AI Financial Agent Builder | arquitetura de agente | SQLite | — | Flask | Dashboard Web | — | MVP v0.3 |
| Confluent Realtime Payment Pipeline | preparação para IA | Kafka / Confluent | **central** | Flink SQL + Consumer | evidências operacionais | — | Em implementação operacional |

## O que o conjunto demonstra

**NEXA Studio** → produto digital + design + arquitetura  
**Document Intelligence Agent** → documentos + automação + IA assistida  
**Agente PMT** → IA + educação + agentes especializados  
**AI Financial Agent Builder** → dados + regras + arquitetura de agente  
**Confluent Realtime Payment Pipeline** → eventos + streaming + engenharia de dados em tempo real

A documentação mantém a distinção entre implementação efetiva, protótipo, preparação operacional e roadmap.

## Navegação

- [Formação e Capacitações](../README.md)
- [Catálogo completo DIO](CATALOGO-COMPLETO-DIO.md)
- [Matriz Capacitação → Projeto → Evidência](MATRIZ-CAPACITACAO-PROJETO.md)
