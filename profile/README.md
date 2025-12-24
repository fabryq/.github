# Fabryq

**Fabryq is the industrial standard way to build Symfony backends.**  
Quality by default. Speed by design. **One way, enforced.**

## Why
Symfony is flexible — and that flexibility often leads to drift: different structures, patterns, shortcuts, and growing technical debt.  
Fabryq prevents drift with **enforced standards**: templates, rules, and automated checks that keep every backend consistent.  
Fabryq turns conventions into gates.

## Core Guardrails
- **One Way Only** — exactly one standard path for structure and modules.
- **Removable Apps** — every app is self-contained; removing one must not break another.
- **No Silent Coupling** — data ownership per app; no cross-app ORM relations.
- **Core stays clean** — infrastructure in the Core, business logic stays in the Apps.

## Repositories
- **core** — kernel, standards, guardrails (the foundation)
- **cli** — generator + enforcer (the “One Way” in practice)
- **platform** — project/app scaffolding and bootstrap setup

**Start here:** read the Core Guardrails, then use the CLI to scaffold your first app.

## Status
Early stage. Hard rules.  
If it’s not standardized, it’s either **becoming a standard** or a **visible, owned exception**.
