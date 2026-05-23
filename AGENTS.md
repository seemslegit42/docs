# AGENTS.md (docs submodule)

Mintlify documentation for **ΛΞVON OS · Weaver**. Parent IDE repo: [seemslegit42/ide](https://github.com/seemslegit42/ide).

## Commands

```bash
bun run dev            # Mintlify preview (this repo)
bun run broken-links   # link check
```

From the IDE repo root: `bun run docs:dev`.

## Layout

- `weaver/*.mdx` — product specifications
- `docs.json` — navigation and ΛΞVON branding (purple `#9810F0`, dark `#020204`)
- `quickstart.mdx` — Bun / `weave` dev setup for the IDE

## New pages (2026-05)

- `weaver/frontend-wiring.mdx` — routes, HUD, registries, `apiService` map
- `weaver/environment.mdx` — `.env` planes, observatory, `env:check`

## Editing

Use MDX frontmatter `title` and `description` on every page. Internal links: `/weaver/architecture` (no `.mdx` suffix).
