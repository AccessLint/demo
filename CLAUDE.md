# CLAUDE.md

## Deployment

- **Production site: https://demo.accesslint.com** — this is the canonical
  production URL for this repo. Use it when scanning, auditing, or linking to
  the deployed site.
- The site is the Next.js dashboard in `dashboards/`, deployed via Netlify
  (see `netlify.toml`).
- PR deploy previews are emitted at
  `https://deploy-preview-<PR-NUMBER>--accesslint-test-fixtures.netlify.app/`
  and are what `.github/workflows/audit-pr.yml` audits.
