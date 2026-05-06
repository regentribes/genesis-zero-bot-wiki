# Memory Wiki

This vault is maintained by the OpenClaw memory-wiki plugin.

- Vault mode: `isolated`
- Render mode: `obsidian`
- Search corpus default: `wiki`

## Vault Structure

```
wiki vault/
├── sources/       ← ADR content via openclaw wiki ingest (code-fence wrapped)
│   ├── index.md
│   └── NNNN-*.md
├── concepts/      ← Claims + relationships (links to sources/)
│   ├── index.md
│   ├── adr-*.md  (ADR concept pages)
│   └── *.md
├── entities/      ← People and organizations
│   ├── index.md
│   └── *.md
├── reports/       ← Auto-generated diagnostics
│   ├── lint.md
│   ├── claim-health.md
│   ├── provenance-coverage.md
│   └── ...
├── syntheses/     ← Synthesis pages
└── index.md      ← Master catalog
```

## How It Works

- `openclaw wiki ingest <file>` — wraps file content in source page with frontmatter
- `openclaw wiki compile` — rebuilds agent-digest.json (claims, relationships, indexes)
- `openclaw wiki lint` — validates wikilinks, surfaces broken refs, contradictions

## STE100 Enforcement

All content uses ASD-STE100: active voice, ≤20 words/sentence, no marketing language.

## Notes
<!-- openclaw:human:start -->
<!-- openclaw:human:end -->
