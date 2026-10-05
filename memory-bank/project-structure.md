# Project Structure

Use this map to find the owning area, then read that area's README before changing it. The root [README](../README.md) has the fuller placement guide.

## Root guidance and context

- [`AGENTS.md`](../AGENTS.md) - agent entry point and links to repository rules.
- [`.agents/rules/memory-bank.md`](../.agents/rules/memory-bank.md) - memory-bank and lesson update rules.
- [`CONTEXT.md`](../CONTEXT.md), [`CONTEXT.es.md`](../CONTEXT.es.md) - company context files.
- [`milestone-1-CONTEXT.md`](../milestone-1-CONTEXT.md) - milestone-specific context.
- [`README.md`](../README.md), [`README.es.md`](../README.es.md) - repository orientation in English and Spanish.

## Product and services

- [`uis/`](../uis/README.md) - user-facing applications and interfaces.
- [`services/`](../services/README.md) - APIs and backend services.

## Data and AI

- `data/` - source data, pipelines, processed data, and evaluation: [`raw/`](../data/raw/README.md), [`pipelines/`](../data/pipelines/README.md), [`process/`](../data/process/README.md), and [`eval/`](../data/eval/README.md).
- [`agents/`](../agents/README.md) - AI agents; [`agents/_template/`](../agents/_template/README.md) is the starter template.
- [`skills/`](../skills/README.md) - reusable agent capabilities and resources.
- [`mcps/`](../mcps/README.md) - Model Context Protocol servers.

## Reuse, automation, and operations

- [`workflows/`](../workflows/README.md) - cross-system automation.
- [`packages/`](../packages/README.md) - reusable packages; `packages/shared/` contains shared TypeScript types.
- [`shared/`](../shared/README.md) - shared assets and lightweight resources.
- [`infra/`](../infra/README.md) - infrastructure and deployment configuration.
- [`scripts/`](../scripts/README.md) - repeatable helper scripts.
- [`internal/`](../internal/README.md) - internal developer tools.

## Documentation and memory

- [`docs/`](../docs/README.md) - stable cross-cutting architecture, decisions, and conventions.
- [`memory-bank/progress.md`](progress.md) - implementation outcomes, blockers, and next steps.
- [`memory-bank/planning-session-transcript.md`](planning-session-transcript.md) - decisions and requirements agreed while creating the memory bank.
- [`memory-bank/lessons/`](lessons/README.md) - verified, student-facing implementation lessons.