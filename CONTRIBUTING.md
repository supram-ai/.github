# Contributing to Supram

Thanks for your interest. These defaults apply to every repository in the `supram-ai` org
unless a repository overrides them.

## Workflow

1. Open an issue describing the change (bug, feature, or docs).
2. Branch from `main`:
   - `feat/<slug>`, `fix/<slug>`, `docs/<slug>`, `chore/<slug>`
3. Keep changes small and focused.
4. Open a pull request. Reference the issue (`Closes #123`).
5. Merge by **squash** once CI is green and a reviewer has approved.

## Requirements

- Do not push directly to `main`; it is protected.
- One logical change per pull request.
- No secrets, tokens, or credentials in commits, tests, or logs. Secrets belong in GitHub
  Actions secrets, Environments, or the platform secret store.
- Update documentation (README, templates, or command contracts) when behavior changes.
- Use clear, conventional commit subjects: `type(scope): description`.

## AI-assisted contributions

AI agents are welcome as tools. When a change is materially produced with an agent, note it in
the commit or pull request (for example `Assisted-by: <agent> <model>`). The human who opens the
pull request remains accountable for the change and must not approve their own work.

## Review

- A different person must approve before merge.
- Reviewers check correctness, security, and adherence to the repository's `AGENTS.md`.
- Deferred (non-blocking) findings should be recorded, not silently dropped.

## Code of conduct

Be direct, technical, and respectful. No harassment or personal attacks.
