# GitHub Actions Training

A forkable companion to https://cropandsoil.org/github-actions/. Use this repo during class and afterward as a self-paced reference.

## Goals
- Understand what GitHub Actions does and why it is useful
- See how automation responds when changes happen in a repository
- Create and run a simple workflow that performs an automatic task
- Recognize how automation supports consistency, organization, and reproducibility

## How to Use This Repo
1. Fork this repository to your account.
2. Enable Actions in your fork if prompted.
3. Open `.github/workflows/` and skim the examples.
4. Make a small commit to trigger a run. Open the Actions tab to observe results.

## Labs
- **Hello Workflow** — `.github/workflows/hello.yml`
- **Markdown Lint** — `.github/workflows/markdown-lint.yml`
- **Python Tests** — `.github/workflows/python-tests.yml`
- **Node CI** — `.github/workflows/node-ci.yml`
- **Artifacts** — `.github/workflows/artifact-demo.yml`
- **Changed Files** — `.github/workflows/changed-files.yml`
- **Reusable Workflow (callee + caller)** — `reusable-lint.yml`, `call-reusable.yml`
- **Scheduled Job** — `schedule-weekly.yml`
- **Permissions** — `permissions-minimum.yml`
- **ADR Policy Check (advanced)** — `adr-policy-check.yml`

Each lab is safe to run in a public fork and uses only free Actions.

## Quick Reference
- Marketplace (free): https://github.com/marketplace?type=actions&pricing=free
- Starter templates: https://github.com/actions/starter-workflows
- Actions cheat sheet: https://github.com/github/actions-cheat-sheet
- Workflow syntax: https://docs.github.com/actions/writing-workflows/workflow-syntax-for-github-actions
- Expressions: https://docs.github.com/actions/learn-github-actions/expressions
- Security hardening: https://docs.github.com/actions/security-guides/security-hardening-for-github-actions

## Troubleshooting
- **Workflow did not trigger**: check `on:` event and branch filters; confirm you pushed to the filtered branch.
- **Permission denied**: set `permissions` explicitly; grant only what the job needs.
- **Cache not restored**: verify the cache key and that the restore key matches your lockfile version.

## Contributing
Open an issue or pull request with improvements that keep the examples beginner friendly and free to run.

## License
Apache-2.0
