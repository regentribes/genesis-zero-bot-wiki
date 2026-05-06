# Memory Wiki

This vault is maintained by the OpenClaw memory-wiki plugin.

- Vault mode: `isolated`
- Render mode: `obsidian`
- Search corpus default: `wiki`

## Architecture (Single-Canonical Per Document)

```
wiki vault/
├── adrs/           # Canonical ADR files — renders as proper Markdown on GitHub
│   ├── 0000-*.md   (ASD-STE100, GitHub-native rendering)
│   ├── ...
│   └── 0007-*.md
├── concepts/       # Concept pages = metadata + claims only (NO content duplication)
│   ├── adr-*.md    (sourceIds → adrs/, claims, relationships)
│   └── *.md
├── sources/        # Lightweight index shells (canonicalPath + URL only)
│   ├── index.md
│   └── NNNN-*.md   (5-line frontmatter + link to adrs/)
└── entities/       # Entity pages
    ├── genesis.md
    └── regen-tribes-community.md
```

## Key Principles

- **One document, one location.** ADR content lives in `adrs/`. No duplication in `sources/`.
- `sources/` = metadata index. `concepts/` = claims. `adrs/` = content.
- All content files render natively on GitHub (no code fences).
- STE100: ASD-STE100 writing style enforced on all content. No marketing language.

## Notes
<!-- openclaw:human:start -->
<!-- openclaw:human:end -->
