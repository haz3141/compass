# Compass

Compass is a minimal reusable MVP starter template for future apps.

It keeps the baseline intentionally small so new products can start with a
modern stack, consistent conventions, and clean documentation without taking on
extra product logic or tooling.

## Requirements

- Node.js 24.x
- pnpm 10.30.3 via `packageManager`

## Included

- Next.js App Router
- TypeScript
- Tailwind CSS v4
- shadcn/ui default-first setup
- `next-themes`
- pnpm

## Philosophy

- Keep the starter small and reusable.
- Prefer modern defaults with minimal friction.
- Treat documentation as part of the starter.
- Avoid adding product-specific features to the baseline.

## Intentionally Out Of Scope

- Authentication, database, analytics, or app-specific flows
- Extra state libraries
- Storybook or heavy repo tooling
- Expanded starter UI beyond the minimal placeholder

## Quick Start

```bash
corepack enable
pnpm install
pnpm dev
```

Open `http://localhost:3000` after the dev server starts.

## Common Commands

```bash
pnpm dev
pnpm check
pnpm lint
pnpm typecheck
pnpm build
pnpm start
```

## Docs

- [Starter Playbook](docs/STARTER_PLAYBOOK.md)
- [GitHub Workflow](docs/WORKFLOW_GITHUB.md)
- [Conventional Commits](docs/CONVENTIONAL_COMMITS.md)

## Template Use

This repository is intended to stay suitable as a lightweight public GitHub
template. Keep changes minimal, production-grade, and easy to understand for
the next app built from it.

It ships with an MIT [LICENSE](LICENSE) and a lightweight pull request
template so public-template hygiene stays clear without adding heavy process.
