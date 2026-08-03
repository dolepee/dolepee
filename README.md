# Dolepee

Verifiable software for agent commerce.

This repository contains the dependency-free static source for `dolepee.com`,
the public index for Dolepee projects. The site uses no client-side JavaScript,
analytics, forms, framework, or runtime service.

## Current work

- [Conviction](https://conviction.dolepee.com) — bounded, non-custodial prediction-market execution.
- [PolicyPool](https://policypool.dolepee.com) — reserve-backed deadline coverage for accepted agent work.
- [GlassDesk](https://glassdesk-nu.vercel.app) — sourced claim-evidence packs with receipts.
- [Foreman](https://foreman-nu-one.vercel.app) — launch-readiness packs for agent builders.

Public repositories are available from the [Dolepee GitHub profile](https://github.com/dolepee).

## Local preview

```sh
python3 -m http.server 4173 --directory public
```

Then open `http://127.0.0.1:4173/`.

## Hosting

The Vercel project should use the `Other` framework preset, no build command,
and `public` as its output directory. The custom domain is intentionally added
only after the production deployment and DNS records have been verified.
