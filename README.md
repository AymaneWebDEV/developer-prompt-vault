# Production System Prompt Vault
### Deterministic System Prompts & Instruction Sets for Claude 3.5, GPT-4o, and Cursor

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Gumroad Download](https://img.shields.io/badge/Full_Vault-Download_on_Gumroad-black?logo=gumroad&logoColor=white)](https://nexusbuilds.gumroad.com/l/developer-prompt-vault)
[![Stars](https://img.shields.io/github/stars/AymaneWebDEV/developer-prompt-vault?style=social)](https://github.com/AymaneWebDEV/developer-prompt-vault)
[![Release: v1.0.0](https://img.shields.io/badge/Release-v1.0.0_Latest-emerald.svg)](https://github.com/AymaneWebDEV/developer-prompt-vault/releases/tag/v1.0.0)

Unconstrained prompts lead to hallucinated imports, omitted edge cases, and verbose conversational filler. This repository contains deterministic, battle-tested instruction sets designed for clean architecture, precision refactoring, automated testing, and security audits.

> ⚡ **Launch Week Special:** Use code `EARLYBIRD` at checkout for **40% OFF** any production starter kit (limited to first 10 builders):
> - [**Next.js 15 AI SaaS Starter Kit ($17.40 with code)**](https://nexusbuilds.gumroad.com/l/nextjs-ai-saas-kit/EARLYBIRD)
> - [**Enterprise n8n AI Automation Vault ($14.40 with code)**](https://nexusbuilds.gumroad.com/l/n8n-ai-automation-vault/EARLYBIRD)
> - [**FastAPI AI Agent Micro-SaaS Kit ($11.40 with code)**](https://nexusbuilds.gumroad.com/l/fastapi-ai-starter-kit/EARLYBIRD)

- [**Download the Complete 150+ Prompt Vault on Gumroad (English // Pay What You Want / $0+)**](https://nexusbuilds.gumroad.com/l/developer-prompt-vault)  
- [**Télécharger l'Édition Française (Pack Prompts Développeur FR // 0€+)**](https://nexusbuilds.gumroad.com/l/pack-prompts-developpeur-fr)  

---

## Free Open-Source Preview vs. Full Production Vault

| Module / Capability | This Free Repository | Full Production Vault ($0+) |
| :--- | :---: | :---: |
| **SOLID Principles Refactoring Engine** | Included | Included |
| **Unit Test Harness Generator (AAA Pattern)** | Included | Included |
| **Master .cursorrules Template** | Basic | Advanced Multi-Framework |
| **Clean Architecture & DDD Scaffolding** | — | 35+ Categorized Schemas |
| **PostgreSQL & MySQL Migration Optimizers** | — | 20+ Production Rulesets |
| **OWASP Top 10 Security SAST Audit** | — | Comprehensive Inspector |
| **Hardened Multi-Stage Dockerfiles** | — | Node, Python, Go, Rust |
| **Hardened CI/CD Pipelines (GitHub Actions)** | — | 15+ Enterprise Workflows |
| **Autonomous n8n AI Agent Workflows** | 1 Included (`workflows/`) | 8 Production Workflows (Full Vault) |
| **French Language Edition Included** | — | Full Bilingual Suite |

👉 [**Get the Full 150+ Instruction Package on Gumroad ($0+)**](https://nexusbuilds.gumroad.com/l/developer-prompt-vault)

---

## Included Sample Prompts

This open-source release provides three foundational instruction sets from the core vault.

### 1. Strict SOLID Principles Refactoring Engine

```markdown
You are a Senior Software Quality Engineer. Refactor the provided code to achieve strict adherence to SOLID design principles:
- Single Responsibility: Split multi-purpose classes/functions into cohesive units.
- Open/Closed: Replace rigid if/switch branching with polymorphism, strategy patterns, or registry tables.
- Liskov Substitution: Ensure derived implementations preserve all base contracts and invariants.
- Interface Segregation: Split monolithic interfaces into client-specific micro-interfaces.
- Dependency Inversion: Decouple high-level domain modules from low-level details using abstract injection.

Rules:
1. Preserve existing public API signatures unless explicitly instructed.
2. Provide a cyclomatic complexity reduction summary before presenting the refactored code.
```

---

### 2. Production Unit Test Harness Generator

```markdown
You are a Lead QA Automation Engineer. Generate a hermetic, deterministic unit test suite for the provided target code.

Requirements:
1. Structure every test using the AAA Pattern (Arrange, Act, Assert).
2. Mock all external boundaries (I/O, database access, network calls, system clock).
3. Cover Happy Paths, Boundary Conditions (empty collections, 0, limits, nulls), and Error Invariants.
4. Each test must be completely independent and capable of parallel execution.
```

---

### 3. Master .cursorrules Drop-In Template

```markdown
# Master .cursorrules Production Template
# Place this file in your project root as .cursorrules

You are an expert senior software engineer working on a mission-critical production codebase.

## Core Behavioral Guidelines:
1. Deterministic & Minimalist: Provide concise, direct solutions. Write minimal, idiomatic, and readable code. Do not apologize or generate verbose conversational filler.
2. Type Safety & Contracts: Always use strict typing. Never use any or untyped dictionaries for domain models.
3. Zero Hallucinated Dependencies: Never introduce new third-party libraries unless explicitly requested. Always check existing manifests first.
4. Error Handling: Every async operation and external call must handle error boundaries gracefully with typed domain errors.
```

---

## Repository Structure

```text
developer-prompt-vault/
├── cursor_rules/
│   └── .cursorrules.example
├── prompts/
│   └── solid_refactor.md
├── workflows/
│   └── 03-Lead-Enrichment-and-ICP-Scorer.json
├── LICENSE
└── README.md
```

---

## Quickstart & Installation

To use these rules in your active projects:
1. Copy `.cursorrules.example` to your repository root and rename it to `.cursorrules`.
2. For Claude or ChatGPT, paste any instruction markdown block as your **System Instructions** before starting a coding session.
3. To unlock the full directory of 150+ production prompts, [download the complete vault on Gumroad](https://nexusbuilds.gumroad.com/l/developer-prompt-vault).

---

## Production Starter Kits & Commercial Blueprints

For developers shipping production SaaS and automated AI infrastructure:

| Starter Kit | Architecture & Tech Stack | Core Capabilities | Access |
| :--- | :--- | :--- | :---: |
| **Next.js 15 AI SaaS Starter Kit** | Next.js 15 (Turbopack), React 19, Supabase SSR, Tailwind | Sub-100ms Edge token streaming, auth guards, metrics dashboard, rate limits | [Get Access ($29)](https://nexusbuilds.gumroad.com/l/nextjs-ai-saas-kit) |
| **Enterprise n8n AI Automation Vault** | 8 Production Workflows, Docker Compose | Autonomous issue triage, lead scoring, RAG pipelines, Stripe dunning | [Get Access ($24)](https://nexusbuilds.gumroad.com/l/n8n-ai-automation-vault) |
| **FastAPI AI Agent Starter Kit** | Python 3.12, FastAPI, Async SSE, Docker, PyTest | Token bucket rate limiting, JWT auth, multi-stage Dockerfile, PyTest suite | [Get Access ($19)](https://nexusbuilds.gumroad.com/l/fastapi-ai-starter-kit) |
| **Developer System Prompt Vault** | 150+ categorized .mdc & system prompt rulesets | Clean architecture, SOLID refactoring, table-driven unit testing | [Download (PWYW)](https://nexusbuilds.gumroad.com/l/developer-prompt-vault) |
| **Pack Prompts Développeur (FR)** | 150+ prompts en français pour développeurs | Architecture logicielle, TDD, refactoring propre | [Télécharger (0€+)](https://nexusbuilds.gumroad.com/l/pack-prompts-developpeur-fr) |

---

## License

Distributed under the [MIT License](LICENSE).  
Maintained by **NexusBuilds**.
