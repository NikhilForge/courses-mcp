# ApexiumDev Engineering Template

A language-agnostic GitHub repository template for structured issues, disciplined pull requests and automated review checks.

## Start here
1. Select **Use this template** on GitHub after publishing this repository as a template.
2. Replace the placeholders in `docs/PROJECT_CONTEXT.md`.
3. Configure issue labels, project board, collaborators and branch protection manually (repository settings do **not** carry over from a template).
4. Adapt `.github/workflows/ci.yml` for the project's actual build/lint/test commands; never mark an unconfigured check as successful.
5. Configure your Codex GitHub connection/MCP separately, with minimum required permissions.

## Workflow
Issue → branch (`feat/123-short-name`, `fix/123-short-name`) → PR → tests / code review → merge.

## Limitations
- `AGENTS.md` guides an AI agent; it does not enforce a GitHub policy.
- GitHub Free protects public repositories, not private repositories, with the same enforced branch-protection controls.
- There is no guarantee automated review finds every bug or vulnerability.
- Template repositories copy files, not all repository settings, issue labels or project boards.
