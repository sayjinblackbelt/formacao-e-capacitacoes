# Projetos de IA

Seleção dos principais projetos do portfólio relacionados a **Inteligência Artificial, agentes, automação e sistemas inteligentes**.

## 1. NEXA Studio

**Foco:** design + tecnologia + comunicação visual + plataforma digital.

O projeto reúne frontend estático, portfolio dinâmico, NEXA Lab, API v1 em Node.js, PostgreSQL schema/repository, integração preparada com Supabase, CI/testes e documentação de governança, QA, segurança e manutenção.

**O que demonstra**
- arquitetura de solução digital;
- integração entre design e tecnologia;
- desenvolvimento Web;
- API e persistência;
- documentação e governança técnica.

[Repositório](https://github.com/sayjinblackbelt/NEXA-Studio) · [Site](https://sayjinblackbelt.github.io/NEXA-Studio/)

> O próprio README classifica os cases atuais como conceituais; portanto, eles não devem ser apresentados como clientes ou resultados comerciais reais.

## 2. Document Intelligence Agent

**Foco:** análise estruturada de documentos com regras determinísticas e IA assistida.

O sistema trabalha com TXT, PDF, PDF escaneado via OCR e DOCX; identifica requisitos, pendências e riscos; produz classificação e score de completude; oferece providers Local, OpenAI e Ollama; mantém histórico SQLite; exporta resultados; possui dashboard, processamento em lote, comparação, eventos de auditoria, autenticação e CI.

**O que demonstra**
- Python e desenvolvimento de APIs;
- processamento documental;
- integração de IA;
- OCR;
- persistência e histórico;
- testes e CI;
- preocupação com autenticação e isolamento de dados.

[Repositório](https://github.com/sayjinblackbelt/document-intelligence-agent)

> O README do projeto o define como demonstrativo e recomenda controles adicionais antes de uso em produção.

## 3. Agente PMT

**Foco:** aplicação de IA em educação, preparação profissional e autonomia digital.

A arquitetura possui três agentes especializados:

- **Agente Carreira:** currículo, vagas, entrevistas e comunicação profissional;
- **Agente Estudos:** planejamento, explicação, exercícios, revisão e aprendizagem;
- **Agente Administração Digital:** Office, Google Workspace e LibreOffice.

O projeto incorpora princípios pedagógicos, segurança e uso responsável de IA.

**O que demonstra**
- arquitetura de agentes;
- IA aplicada à educação;
- desenho de fluxos de aprendizagem;
- integração entre tecnologia e empregabilidade;
- preocupação com autonomia e responsabilidade no uso da IA.

[Repositório](https://github.com/sayjinblackbelt/Agente-PMT) · [Demonstração](https://sayjinblackbelt.github.io/Agente-PMT/)

## 4. AI Financial Agent Builder

**Foco:** contexto financeiro estruturado, análise determinística e preparação para um agente conversacional.

O MVP utiliza Flask, SQLite, onboarding guiado, perfil financeiro, transações, categorias, orçamentos, alertas, resumo mensal, comparação, tendências, insights e configuração de agente.

Um princípio arquitetural importante é manter os **cálculos financeiros fora do modelo de IA**: dados e regras produzem os fatos; a futura IA deverá interpretar e apresentar o contexto.

**O que demonstra**
- arquitetura de agentes;
- análise determinística;
- Python/Flask;
- SQLite e persistência;
- APIs;
- dashboard;
- testes e CI;
- preocupação com segurança e limites de autonomia.

[Repositório](https://github.com/sayjinblackbelt/AI-Financial-Agent-Builder) · [Case](https://sayjinblackbelt.github.io/AI-Financial-Agent-Builder/)

> O README classifica o projeto como MVP e informa que a próxima etapa é a validação manual da experiência completa e a evolução para a camada conversacional.

## Visão conjunta

| Projeto | IA / Agentes | Software | Dados | Educação | Design |
|---|:---:|:---:|:---:|:---:|:---:|
| NEXA Studio | ◐ | ● | ◐ | — | ● |
| Document Intelligence Agent | ● | ● | ● | — | — |
| Agente PMT | ● | ● | ◐ | ● | ◐ |
| AI Financial Agent Builder | ● | ● | ● | — | ◐ |

**Legenda:** ● = eixo central/documentado · ◐ = componente relacionado · — = não é foco do projeto.

## Padrão de evidência

Os quatro projetos mostram aplicações diferentes de IA:

**IA aplicada a documentos → IA aplicada à educação → arquitetura de agentes → IA sobre dados estruturados.**

O portfólio deve apresentar cada projeto pelo que está efetivamente documentado, diferenciando **protótipo, MVP, concept case e aplicação validada**.
