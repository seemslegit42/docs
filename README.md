# ΛΞVON OS · Weaver documentation

Mintlify site for **Weaver Studio** and the **Nexus Swarm API**. This repository is a [git submodule](https://github.com/seemslegit42/ide) at `docs/` in the IDE monorepo.

## Prerequisites

- [Bun](https://bun.sh) 1.1+
- **Node 20 LTS** for the Mintlify CLI (Node 25+ is not supported by `mint` yet)

## Local preview

From this directory:

```bash
bun install   # optional; mint is also available via the parent IDE repo
bun run dev
```

From the **parent IDE repo**:

```bash
bun run docs:dev
```

Open http://localhost:3000 (Mintlify picks the next free port if 3000 is taken).

## Other commands

```bash
bun run broken-links
bun run update
```

## Publishing

Connect this repo in the [Mintlify dashboard](https://dashboard.mintlify.com). Pushes to `main` deploy automatically when the GitHub app is installed.

## Structure

| Path | Purpose |
| :--- | :--- |
| `weaver/*.mdx` | Product and platform specifications |
| `quickstart.mdx` | Local dev setup (Bun / `weave`) |
| `docs.json` | Site theme, nav, and branding |
