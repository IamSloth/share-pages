# Share Pages

Small public landing pages for quick sharing through GitHub Pages.

Live site:

- https://iamsloth.github.io/share-pages/

## Structure

```text
pages/
└── jamsil-baseball-20260522/
    ├── index.html
    └── assets/
```

## Local Preview

Open any page's `index.html` in a browser, or serve the repo root locally:

```powershell
python -m http.server 4173
```

Current page:

- https://iamsloth.github.io/share-pages/pages/jamsil-baseball-20260522/

## Deploy

Recommended setup:

- Repository: `share-pages`
- Visibility: public
- Source: `main` branch, repository root
- Root index: `index.html`
- Page URL path: `/pages/jamsil-baseball-20260522/`

Keep public pages free of payment details, ticket QR codes, account numbers, tokens, and private project materials.
