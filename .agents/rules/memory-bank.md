# Memory-Bank Rules

## Start of a task

- Read the root `AGENTS.md`, this file, and `memory-bank/progress.md`.
- Read only the relevant sections of `memory-bank/project-structure.md` and lessons, then consult the applicable folder README and company context.

## After implementation

- In every implementation completion response, explain the intent of the change, how the implementation works, and representative examples from the changed code with plain-language explanations. Link examples to the relevant files; keep excerpts small and useful for learning.
- Update `memory-bank/progress.md` after meaningful work with outcomes, blockers, and the next useful step. Do not log routine noise.
- Update `memory-bank/project-structure.md` when meaningful paths or responsibilities change.
- Add or update a lesson only when the implementation provides verified, reusable learning for students. Do not create a lesson for every implementation or invent details. Prefer updating a matching existing lesson over duplicating its topic.

## Lessons

- A lesson explains the problem or goal, why the approach was chosen, how it works, and relevant validation. Use concise examples from the actual implementation and explain them; do not copy whole source files.
- Name new lessons `NN-<project_name>.md`, with a concise kebab-case project name. Start numbering at `01` and use the next unused number in sequence. Do not renumber existing lessons.
- Before creating a new lesson, ask the user to provide the project name if they have not already supplied it. If the name or matching topic already has a lesson, clarify whether to update it rather than create a duplicate.
- Keep the lessons index current when adding, renaming, or removing a lesson.

## Boundaries

- Treat source code and `CONTEXT.md` as authoritative for implementation and domain facts.
- Keep stable architecture and cross-cutting guidance in `docs/`; use the memory bank for evolving project history, navigation, and verified lessons.
- `.agents/rules/` is explicitly referenced by `AGENTS.md`; do not assume every agent host automatically loads it.