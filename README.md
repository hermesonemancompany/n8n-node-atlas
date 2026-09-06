# n8n Node Atlas

A static engineering documentation site for n8n core nodes.

- Official package: `n8n-nodes-base@2.15.1`
- Catalog entries: 438
- Includes architecture diagrams, production patterns, expressions, reliability/security guidance, recipes, and searchable node inventory.
- Generated output: `site/index.html`

## Scope

The catalog is generated from the official core package manifest at build time. n8n community nodes and version-specific operation parameters are not represented as core coverage.

## Local build

```bash
python3 build_site.py
```

The generated `site/` directory is deployed automatically to GitHub Pages on every push to `main`.
