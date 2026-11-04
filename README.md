# Alva docs

User documentation for [Alva](https://alvahq.com), published at [docs.alvahq.com](https://docs.alvahq.com) with Mintlify.

| Item | Where |
|------|-------|
| Pages | `*.mdx`, one folder per navigation group |
| Navigation, theme, links | `docs.json` |
| Writing rules for agents | `.cursor/rules/agent.mdc` |
| Source of truth | The product repository (`KabeZiller/crm`): `docs/features/`, `CHANGELOG.md` and the code |
| API endpoint pages | Generated from `https://app.alvahq.com/api/v1/openapi` (the same document as the in-app API Console). A docs deploy is required after the production API changes |

## Preview locally

```bash
npx mint dev
```

Opens on `http://localhost:3000`.

## Check links

```bash
npx mint broken-links
```

## Publish

Push to `main`. Mintlify deploys automatically.
