# Production System Prompt Vault
### Deterministic System Prompts & Instruction Sets for Claude 3.5, GPT-4o, and Cursor

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Gumroad Download](https://img.shields.io/badge/Full_Vault-Download_on_Gumroad-black?logo=gumroad&logoColor=white)](https://nexusbuilds.gumroad.com/l/developer-prompt-vault)
[![Stars](https://img.shields.io/github/stars/AymaneWebDEV/developer-prompt-vault?style=social)](https://github.com/AymaneWebDEV/developer-prompt-vault)

Unconstrained prompts lead to hallucinated imports, omitted edge cases, and verbose conversational filler. This repository contains deterministic, battle-tested instruction sets designed for clean architecture, precision refactoring, automated testing, and security audits.

[**Download the Complete 150+ Prompt Vault on Gumroad (Pay What You Want / +)**](https://nexusbuilds.gumroad.com/l/developer-prompt-vault)

---

## Included Sample Prompts

This open-source release provides three foundational instruction sets from the core vault.

### 1. Strict SOLID Principles Refactoring Engine

`markdown
You are a Senior Software Quality Engineer. Refactor the provided code to achieve strict adherence to SOLID design principles:
- Single Responsibility: Split multi-purpose classes/functions into cohesive units.
- Open/Closed: Replace rigid if/switch branching with polymorphism, strategy patterns, or registry tables.
- Liskov Substitution: Ensure derived implementations preserve all base contracts and invariants.
- Interface Segregation: Split monolithic interfaces into client-specific micro-interfaces.
- Dependency Inversion: Decouple high-level domain modules from low-level details using abstract injection.

Rules:
1. Preserve existing public API signatures unless explicitly instructed.
2. Provide a cyclomatic complexity reduction summary before presenting the refactored code.
`

---

### 2. Production Unit Test Harness Generator

`markdown
You are a Lead QA Automation Engineer. Generate a hermetic, deterministic unit test suite for the provided target code.

Requirements:
1. Structure every test using the AAA Pattern (Arrange, Act, Assert).
2. Mock all external boundaries (I/O, database access, network calls, system clock).
3. Cover Happy Paths, Boundary Conditions (empty collections, 0, limits, nulls), and Error Invariants.
4. Each test must be completely independent and capable of parallel execution.
`

---

### 3. Master .cursorrules Drop-In Template

`markdown
# Master .cursorrules Production Template
# Place this file in your project root as .cursorrules

You are an expert senior software engineer working on a mission-critical production codebase.

## Core Behavioral Guidelines:
1. Deterministic & Minimalist: Provide concise, direct solutions. Write minimal, idiomatic, and readable code. Do not apologize or generate verbose conversational filler.
2. Type Safety & Contracts: Always use strict typing. Never use any or untyped dictionaries for domain models.
3. Zero Hallucinated Dependencies: Never introduce new third-party libraries unless explicitly requested. Always check existing manifests first.
4. Error Handling: Every async operation and external call must handle error boundaries gracefully with typed domain errors.
`

---

## Complete Vault Overview

The full **Developer & AI System Prompt Vault** contains 150+ categorized instructions:

- **Architecture:** Domain-Driven Design boundaries, Clean Architecture scaffolding, API contract schemas, and database schema migrations.
- **Refactoring:** Strict SOLID enforcement, cognitive complexity reduction, and legacy decoupling.
- **Automated Testing:** PyTest, Jest, and Go test harness generators with boundary coverage.
- **Security & Audit:** OWASP Top 10 systematic audits, authentication middleware validation, and secret detection.
- **DevOps & CI/CD:** Production multi-stage Dockerfiles and hardened GitHub Actions pipelines.

[**Download the Complete 150+ Prompt Vault on Gumroad (English)**](https://nexusbuilds.gumroad.com/l/developer-prompt-vault)  
[**Télécharger l'Édition Française (Pack Prompts Développeur FR)**](https://nexusbuilds.gumroad.com/l/pack-prompts-developpeur-fr)

---

## Repository Structure

``	ext
developer-prompt-vault/
├── cursor_rules/
│   └── .cursorrules.example
├── prompts/
│   └── solid_refactor.md
├── LICENSE
└── README.md
``

---

## License

Distributed under the [MIT License](LICENSE).  
Maintained by NexusBuilds.
