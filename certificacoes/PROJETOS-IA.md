# Projetos de IA — Evidências técnicas e aplicação

Esta página detalha quatro projetos prioritários de IA e arquitetura de soluções do portfólio e sua relação com a formação em IA, GenAI, agentes, automação, desenvolvimento e educação.

> A descrição abaixo é derivada da documentação atual dos próprios repositórios. Onde o projeto ainda está em roadmap ou protótipo, isso é explicitamente indicado.

## 01 · NEXA Studio

**Papel no portfólio:** ecossistema multidisciplinar que integra design, estratégia, tecnologia e comunicação visual, com experimentação tecnológica documentada.

**Competências demonstradas:** Design, comunicação visual, frontend, Node.js/API, PostgreSQL, Supabase, CI, testes, governança, QA, segurança e arquitetura de produto digital.

**Arquitetura documentada:** frontend estático no GitHub Pages; `data/portfolio.json`; NEXA Lab; API v1 em Node.js; PostgreSQL schema v1; integração preparada com Supabase; CI e testes automatizados.

**Evidências:** 14 concept cases, portfolio dinâmico, carrossel de projetos e gates técnicos 4.10.1 e 4.10.2 registrados como PASS.

**Maturidade:** `4.10.3-A — HOSTING PREPARATION / IN VALIDATION`. A API ainda não está hospedada publicamente; o roadmap prevê deploy, integração pública, autenticação, RLS, segurança, beta e preparação comercial.

**Links:** [Repositório](https://github.com/sayjinblackbelt/NEXA-Studio) · [Site](https://sayjinblackbelt.github.io/NEXA-Studio/) · [NEXA Lab](https://sayjinblackbelt.github.io/NEXA-Studio/studio.html)

## 02 · Document Intelligence Agent

**Papel no portfólio:** aplicação de IA assistida e automação para análise estruturada de documentos.

**Competências demonstradas:** Python, processamento de documentos, OCR, análise determinística, IA assistida, JSON estruturado, SQLite, APIs, JWT, Docker, testes, GitHub Actions/CI, dashboards, processamento em lote, comparação documental e auditoria.

**Fluxo:** TXT/PDF/DOCX → extração de texto → análise determinística → IA Local/OpenAI/Ollama → JSON estruturado → SQLite → histórico, filtros e exportação.

**Diferencial técnico:** a solução possui uma camada determinística anterior à análise assistida por IA, seguida de contrato JSON estruturado.

**Funcionalidades:** PDF e DOCX, OCR, requisitos, pendências, riscos, score de completude, providers Local/OpenAI/Ollama, histórico, exportação, dashboard, lote de até 20 arquivos, comparação e auditoria.

**Maturidade:** projeto demonstrativo com API, interface, testes, Docker e CI documentados. O README recomenda controles adicionais antes de uso em produção para dados sensíveis.

**Link:** [Repositório](https://github.com/sayjinblackbelt/document-intelligence-agent)

## 03 · Agente PMT

**Papel no portfólio:** aplicação de IA em educação, empregabilidade, aprendizagem e autonomia digital.

**Arquitetura:** três agentes especializados — Agente Carreira, Agente Estudos e Agente Administração Digital.

**Competências demonstradas:** arquitetura de agentes, IA aplicada à educação, design de experiência, tecnologia educacional, engenharia de prompts, segurança e responsabilidade em IA e organização de fluxos.

**Diferencial pedagógico:** o projeto declara que a IA deve funcionar como mediadora da aprendizagem, e não como substituta do estudante. Também incorpora princípios da Pedagogia Heulosófica.

**Segurança:** não inventar experiências ou competências; não tomar decisões profissionais pelo estudante; minimizar coleta de dados; não solicitar senhas; ensinar uso responsável da IA.

**Maturidade:** protótipo publicado no GitHub Pages. A arquitetura dos três agentes, documentação e validação estrutural C1–C8 estão registradas; testes de integração, piloto PMT, avaliação pedagógica e versão 2.0 permanecem no roadmap.

**Links:** [Repositório](https://github.com/sayjinblackbelt/Agente-PMT) · [Demo](https://sayjinblackbelt.github.io/Agente-PMT/)

## 04 · AI Financial Agent Builder

**Papel no portfólio:** projeto que combina dados estruturados, análise determinística e arquitetura de agente.

**Competências demonstradas:** Python, Flask, SQLite, modelagem de dados, análise determinística, dashboards, API, configuração de agentes, geração de prompts, testes, GitHub Actions/CI e arquitetura local-first.

**Fluxo:** Guided Onboarding → Financial Profile → Flask API → SQLite → Financial Analyzer → Insights/Alerts/Trends → Agent Configuration → Future Conversational AI.

**Decisão arquitetural:** a matemática financeira permanece fora do modelo de IA: dados e regras produzem os fatos; a futura IA interpreta intenção e apresenta contexto.

**MVP:** onboarding financeiro, perfil, receitas/despesas, categorias, orçamentos, alertas, resumo mensal, comparação, tendências, insights por regras, configuração do agente, API, dashboard, testes e CI.

**Limites:** não executa transações, não solicita credenciais bancárias, não toma decisões autônomas de investimento, não deve inventar dados e deve pedir esclarecimento quando houver dados insuficientes.

**Maturidade:** `MVP v0.3 — validated core / browser validation next`. A próxima etapa documentada é a validação manual da experiência completa.

**Links:** [Repositório](https://github.com/sayjinblackbelt/AI-Financial-Agent-Builder) · [Case interativo](https://sayjinblackbelt.github.io/AI-Financial-Agent-Builder/)

## Comparação técnica

| Projeto | IA / Agentes | Dados | Backend | Interface | Educação | Maturidade |
|---|---|---|---|---|---|---|
| NEXA Studio | arquitetura/experimentação | PostgreSQL | Node.js API | GitHub Pages / NEXA Lab | — | Protótipo em validação |
| Document Intelligence Agent | IA assistida | SQLite | Python API | Web | — | Demonstrativo com CI |
| Agente PMT | 3 agentes | — | arquitetura de agentes | GitHub Pages | **central** | Protótipo publicado |
| AI Financial Agent Builder | arquitetura de agente | SQLite | Flask | Dashboard Web | — | MVP v0.3 |

## O que os quatro projetos demonstram

**NEXA Studio** → produto digital + design + arquitetura  
**Document Intelligence Agent** → documentos + automação + IA assistida  
**Agente PMT** → IA + educação + agentes especializados  
**AI Financial Agent Builder** → dados + regras + arquitetura de agente

O conjunto demonstra capacidade de projetar soluções digitais para problemas distintos, documentando arquitetura, limitações, testes, roadmap e aplicação.

## Navegação

- [Formação e Capacitações](../README.md)
- [Catálogo completo DIO](CATALOGO-COMPLETO-DIO.md)
- [Matriz Capacitação → Projeto → Evidência](MATRIZ-CAPACITACAO-PROJETO.md)