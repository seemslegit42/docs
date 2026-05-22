# Contributing to Weaver docs

This site uses [Mintlify](https://mintlify.com). The **Weaver** product pages live under `weaver/`.

## Setup

```bash
bun install
bun run dev
```

## Style

- Prefer clear, technical prose in guides; codex tone is fine in specs under `weaver/`.
- One topic per page; link to [blueprint](/weaver/blueprint) for persistence canon.
- Use `bun` / `bunx` in all command examples (this monorepo is Bun-first).

## Pull requests

1. Branch from `main`
2. Run `bun run broken-links` before opening a PR
3. Mintlify deploys on merge to `main`
