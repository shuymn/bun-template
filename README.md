# bun-template

Minimal Bun template with:

- GitHub Actions CI
- Biome lint/format
- Lefthook hooks (`pre-commit`, `commit-msg`)
- Commitlint

## Setup

```bash
bun install
```

`postinstall` runs `lefthook install` automatically.

## Scripts

```bash
bun run lint
bun run fmt
bun run typecheck
bun run check
```
