# GitHub Actions usage policy

Effective 2026-09-27: the account's GitHub Actions quota is exhausted.

Until the user explicitly lifts this restriction:

- Do not trigger, re-run, dispatch, or rely on GitHub Actions.
- Run tests, research jobs, builds, and validation locally or manually.
- Use `[skip ci]` in commits that would otherwise trigger CI where supported.
- Do not treat a missing remote CI result as a code failure when local/manual verification is available.
- If a task truly requires hosted Actions, stop and report that the quota restriction blocks it instead of consuming or retrying Actions.

This is a repository-wide operating constraint for future work.
