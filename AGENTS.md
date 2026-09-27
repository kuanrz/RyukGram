# Agent instructions

GitHub is the source of truth. Inspect the latest repository state before starting work.
## GitHub Actions quota constraint
- Do not trigger, rerun, or rely on GitHub Actions unless the user explicitly lifts this constraint.
- The user's GitHub Actions quota is currently exhausted.
- Run tests and validation locally or manually instead.
- When committing or pushing while this constraint is active, include `[skip ci]` in the commit message when applicable so push/pull-request workflows do not consume Actions minutes.
- Leave existing workflow files unchanged unless the user explicitly asks to modify or remove them.

