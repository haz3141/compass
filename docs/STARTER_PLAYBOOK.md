# Starter Playbook

This repository is a reusable MVP starter built on Next.js App Router,
TypeScript, Tailwind CSS, and shadcn/ui. It is intentionally minimal so new
products can start from a clean baseline instead of a framework pile.

## Agreed Stack

- Next.js (App Router)
- TypeScript
- Tailwind CSS v4
- shadcn/ui (default init + core primitives)
- `next-themes` for dark/light theme handling
- `lucide-react` for icons
- pnpm for package management

## Starter Principles

- Keep the dependency surface intentionally small.
- Prefer modern defaults and low-friction setup.
- Preserve reusability over app-specific convenience.
- Update docs whenever setup or workflow changes.

## Engineering Rules

- Keep diffs minimal and production-grade.
- Prefer Server Components; use `"use client"` only where needed.
- Avoid adding extra dependencies unless required.
- No auth, database, analytics, or app-specific screens in the starter.
- Use pnpm only for package operations.

## Day-1 Commands

```bash
pnpm install
pnpm dev
pnpm lint
pnpm typecheck
pnpm build
```

## Commit and CI Contract

- Use Conventional Commits (`type(scope): summary`).
- Keep commits atomic (one logical change per commit).
- CI must pass `lint`, `typecheck`, and `build` on PRs and pushes to `main`.
- Keep GitHub hygiene lightweight and practical.

See also:
- `docs/WORKFLOW_GITHUB.md`
- `docs/CONVENTIONAL_COMMITS.md`
