# Gabriel Dantas

> 🌐 [Read in English](README.md) · **Português (PT-BR)**

**AI Product Manager & Context Engineer** · Gestão de Produtos Digitais @ **Braskem** · **CAPM®**

Conectando **Product Discovery & Governança de Negócio** (RICE/WSJF, KPIs, Taxa de Adoção) com **Engenharia Determinística de IA** (Model Context Protocol, Camadas Semânticas, Prefix Caching, Guardrails AST e TDD).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gdso-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gdso)
[![App Online](https://img.shields.io/badge/Live_Demo-Data_Context_Engine-6366F1?style=for-the-badge&logo=streamlit&logoColor=white)](https://data-context-engine.streamlit.app)
[![Email](https://img.shields.io/badge/Email-gabrielsilva07032002%40gmail.com-18181B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabrielsilva07032002@gmail.com)

📍 São Paulo, Brasil · Disponível para Remoto (Global/LATAM) & Híbrido SP

---

### Projetos em Destaque

| Projeto | Problema & Arquitetura | Impacto Verificado & Engenharia |
| :--- | :--- | :--- |
| **[Data Context Engine (DCE)](https://github.com/dantinha/data-context-engine)**<br/>*[Demo Online ↗](https://data-context-engine.streamlit.app)* | Motor de Context Engineering e Governança em 4 camadas para LLMs analíticos sobre **DuckDB** e **dbt**, expondo servidor **FastMCP** com 7 ferramentas atômicas, roteamento por grafo BFS e sandbox **SQLGlot AST**. | • **83,3% → 86,7%** (`26/30`) de acurácia Text-to-SQL (vs. 33,3% L1 ingênuo) em 30 benchmarks gold<br/>• **-61,3% em tokens** com Prefix Caching estático (62,8% cacheável)<br/>• **100% bloqueio** em 24 vetores de SQL injection/mutação<br/>• **83 testes automatizados** (`pytest` + Streamlit `AppTest`) |
| **[Voz Guia (Android)](https://github.com/dantinha/voz-guia-android)** | Agente assistivo nativo Android (**Kotlin / Jetpack Compose**) que substitui fluxos mecânicos do TalkBack para pessoas com perda visual recente, usando `AccessibilityService`, voz offline (`Piper TTS` / `Vosk`) e Modo Cuidador. | • **PRD v2.0** completo (5 Épicos, 18 Funcionalidades, Gherkin)<br/>• Contrato determinístico de feedback háptico **<50ms**<br/>• **34 suítes / 150 testes TDD** aprovados via Gradle<br/>• QA em emulador + configuração de release `AAB` assinada |
| **[Text-to-CAD](https://github.com/dantinha/text-to-cad)** | Motor de CAD 3D paramétrico por linguagem natural: o Gemini gera apenas uma **IR** CSG validada por Zod (nunca malha bruta) com loop de reparo, avaliada por **manifold-3d** em Web Worker e renderizada com **React Three Fiber**; exporta `.stl` binário e `.scad`. | • **201 testes unitários** (95%+ cobertura) + **5/5 E2E Playwright**<br/>• TypeScript `strict`, ESLint limpo, bloqueio de segredos no pré-commit + CI<br/>• Proxy blindado `/api/gemini` (Cloudflare Worker) + BYOK (`sessionStorage`) |
| **[CertRadar](https://github.com/dantinha/cert-radar)** | Motor pessoal a custo zero para curadoria de certificações e radar de vouchers (**Python / SQLite / CLI / SPA**) com matching determinístico em 4 pilares, checagem de links ativos e alertas desduplicados. | • **158 testes automatizados** aprovados (**100% pass rate**)<br/>• Alertas anti-spam no Windows Toast & Telegram (`activation_epoch`)<br/>• Pronto para deploy PWA (`Dockerfile` + `render.yaml`) |
| **Classifica_Lead** *(Privado / B2B)* | Plataforma B2B multi-tenant de qualificação inbound/outbound com **FastAPI**, **Gemini Structured Outputs**, rubricas dinâmicas, LangGraph RAG e conformidade LGPD Art. 18. | • Fallback resiliente em 4 provedores CNPJ (`BrasilAPI → MinhaReceita → ReceitaWS → CNPJ.ws`)<br/>• Pré-filtro preventivo CNAE com zero tokens |

---

### Stack & Competências Principais

- **Produto & Governança:** Product Discovery, Escopo de MVP, Roadmaps, Priorização RICE/WSJF, Jira & Confluence, OKRs/KPIs, Taxa de Adoção, CAPM® (PMBOK).
- **IA & Context Engineering:** Model Context Protocol (`FastMCP`), Prefix Caching, Camadas Semânticas (`dbt`), Recuperação Híbrida em Grafo (BM25 + BFS), Structured Outputs (Gemini API), Guardrails SQL AST (`sqlglot`), Benchmarks & Evals de LLMs.
- **Dados & Engenharia:** Python (`pytest`, `FastAPI`, `Pydantic`), SQL, DuckDB, Power BI (`DAX/M`), Kotlin / Jetpack Compose, TypeScript / React / Three.js.

---

### Formação & Credenciais

- **MBA em Business Intelligence** — FIAP *(2025 – 2026)*
- **MBA em Automação Industrial** — USP-POLI *(2023 – 2025)*
- **Bacharelado em Engenharia Elétrica** — Universidade São Judas *(2024 – 2026)*
- **Tecnólogo em Microeletrônica** — FATEC-SP *(2020 – 2023)*
- **CAPM® (Certified Associate in Project Management)** — PMI
