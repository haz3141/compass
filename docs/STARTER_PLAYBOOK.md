# Starter Playbook

This repository is a reusable MVP starter built on Next.js App Router, TypeScript, Tailwind CSS, and shadcn/ui. It is intentionally minimal so new products can start from a clean baseline.

## Agreed Stack

- Next.js (App Router)
- TypeScript
- Tailwind CSS (default setup)
- shadcn/ui (default init + core primitives)
- `next-themes` for dark/light theme handling
- `lucide-react` for icons
- pnpm for package management

## Engineering Rules

- Keep diffs minimal and production-grade.
- Prefer Server Components; use `"use client"` only where needed.
- Avoid adding extra dependencies unless required.
- No auth, database, analytics, or app-specific screens in the starter.

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

See also:
- `docs/WORKFLOW_GITHUB.md`
- `docs/CONVENTIONAL_COMMITS.md`
