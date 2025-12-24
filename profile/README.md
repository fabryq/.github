<img src="https://github.com/fabryq/.github/blob/main/fabryq-schriftzug-github.jpg" alt="drawing" width="400"/>


**Fabryq provides an industrial-style standard path to build Symfony backends.**  
Quality by default. Speed by design. **One way, enforced.**

## Why
Symfony is flexible — and that flexibility often leads to drift: different structures, patterns, shortcuts, and growing technical debt.  
Fabryq reduces drift by enforcing a single standard path through **templates**, **rules**, and **automated checks**.  
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

## Start here
Read the **Core Guardrails**, then use the **CLI** to scaffold your first app.

## Why the “q” in Fabryq?
The **q** is a daily reminder of what the standard path is optimized for.

1. **Quality**  
   Quality by default through enforced standards and automated checks.

2. **Quick**  
   Faster delivery by removing boilerplate and decision paralysis.

3. **Queue**  
   One track, one path — like a train on rails: no detours, no shortcuts.

4. **Query**  
   Clean boundaries around data access: resources and use-cases stay decoupled, cross-app access happens via contracts and IDs.

## Status
Early stage. Hard rules.  
If it’s not standardized, it’s either **becoming a standard** or a **visible, owned exception**.
