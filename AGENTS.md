# AGENTS.md (docs submodule)

Mintlify documentation for **ΛΞVON OS · Weaver**. Parent IDE repo: [seemslegit42/ide](https://github.com/seemslegit42/ide).

## Commands

```bash
bun run dev            # Mintlify preview (this repo)
bun run broken-links   # link check
```

From the IDE repo root: `bun run docs:dev`.

## Layout

- `weaver/*.mdx` — product specifications (migrated from IDE `docs-temp/`)
- `docs.json` — navigation and ΛΞVON branding (purple `#9810F0`, dark `#020204`)
- `quickstart.mdx` — Bun / `weave` dev setup for the IDE

## Editing

Use MDX frontmatter `title` and `description` on every page. Internal links: `/weaver/architecture` (no `.mdx` suffix).
