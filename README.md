# Gabriel Dantas

> 🌐 **English** · [Leia em Português (PT-BR)](README.pt-BR.md)

**AI Product Manager & Context Engineer** · Digital Product Management @ **Braskem** · **CAPM®**

Bridging **Product Discovery & Business Governance** (RICE/WSJF, KPIs, Adoption Rate) with **Deterministic AI Engineering** (Model Context Protocol, Semantic Layers, Prefix Caching, AST Guardrails, and TDD).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gdso-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gdso)
[![Live AI App](https://img.shields.io/badge/Live_Demo-Data_Context_Engine-6366F1?style=for-the-badge&logo=streamlit&logoColor=white)](https://data-context-engine.streamlit.app)
[![Email](https://img.shields.io/badge/Email-gabrielsilva07032002%40gmail.com-18181B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabrielsilva07032002@gmail.com)

📍 São Paulo, Brazil · Open to Remote (Global/LATAM) & Hybrid SP

---

### Featured Projects

| Project | Problem & Architecture | Verified Impact & Engineering |
| :--- | :--- | :--- |
| **[Data Context Engine (DCE)](https://github.com/dantinha/data-context-engine)**<br/>*[Live Demo ↗](https://data-context-engine.streamlit.app)* | 4-layer Context Engineering & Governance engine for analytical LLMs over **DuckDB** and **dbt**, exposing a **FastMCP** server with 7 atomic tools, BFS relational graph routing, and **SQLGlot AST** sandboxing. | • **83.3% → 86.7%** (`26/30`) Text-to-SQL accuracy (vs. 33.3% naive L1 dump) across 30 gold benchmarks<br/>• **-61.3% token usage** via static Prefix Caching (62.8% cacheable)<br/>• **100% blocked** across 24 SQL injection/mutation attack vectors<br/>• **83 automated tests** (`pytest` + Streamlit `AppTest`) |
| **[Voz Guia (Android)](https://github.com/dantinha/voz-guia-android)** | Native Android assistive AI agent (**Kotlin / Jetpack Compose**) replacing mechanical TalkBack flows for users with recent visual loss, powered by `AccessibilityService`, offline voice (`Piper TTS` / `Vosk`), and Caregiver UI. | • Full **PRD v2.0** (5 Epics, 18 Features, Gherkin User Stories)<br/>• **<50ms** deterministic haptic feedback contract<br/>• **34 suites / 150 TDD unit tests** passing via Gradle<br/>• Emulator E2E QA & signed release bundle (`AAB`) config |
| **[Text-to-CAD](https://github.com/dantinha/text-to-cad)** | Natural-language → parametric 3D CAD engine: Gemini emits a Zod-validated CSG **IR** (never raw geometry) with a 2-step repair loop, evaluated by **manifold-3d** in a Web Worker and rendered with **React Three Fiber**; deterministic **OpenSCAD** + binary `.stl` export. | • **201 unit tests** (95%+ coverage) + **5/5 Playwright E2E** passing<br/>• TypeScript `strict`, ESLint clean, secret scanning pre-commit + CI<br/>• Hardened `/api/gemini` Cloudflare Worker proxy + BYOK (`sessionStorage`) |
| **[CertRadar](https://github.com/dantinha/cert-radar)** | Zero-cost personal upskilling & official exam voucher engine (**Python / SQLite / CLI / SPA**) with deterministic 4-pillar career-gap matching, link liveness checks, and deduplicated deadline alerts. | • **158 automated tests** passing (**100% pass rate**)<br/>• Anti-spam Windows Toast & Telegram alerts (`activation_epoch`)<br/>• `Dockerfile` + `render.yaml` PWA deploy ready |
| **Classifica_Lead** *(Private / B2B)* | Multi-tenant B2B inbound/outbound lead qualification platform built with **FastAPI**, **Gemini Structured Outputs**, dynamic tenant rubrics, LangGraph RAG, and LGPD Art. 18 opt-out compliance. | • 4-provider resilient CNPJ enrichment fallback (`BrasilAPI → MinhaReceita → ReceitaWS → CNPJ.ws`)<br/>• Zero-token CNAE pre-filtering |

---

### Core Stack & Competencies

- **Product & Governance:** Product Discovery, MVP Scoping, Roadmaps, RICE/WSJF Prioritization, Jira & Confluence, OKRs/KPIs, Adoption Rate, CAPM® (PMBOK).
- **AI & Context Engineering:** Model Context Protocol (`FastMCP`), Prefix Caching, Semantic Layers (`dbt`), Hybrid Graph Retrieval (BM25 + BFS), Structured Outputs (Gemini API), AST SQL Guardrails (`sqlglot`), LLM Benchmarks & Evals.
- **Data & Engineering:** Python (`pytest`, `FastAPI`, `Pydantic`), SQL, DuckDB, Power BI (`DAX/M`), Kotlin / Jetpack Compose, TypeScript / React / Three.js.

---

### Education & Credentials

- **MBA in Business Intelligence** — FIAP *(2025 – 2026)*
- **MBA in Industrial Automation** — USP-POLI *(2023 – 2025)*
- **B.Sc. in Electrical Engineering** — Universidade São Judas *(2024 – 2026)*
- **Associate Degree in Microelectronics** — FATEC-SP *(2020 – 2023)*
- **CAPM® (Certified Associate in Project Management)** — PMI
