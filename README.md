# Craftview

Craftview Software GmbH is a Frankfurt-headquartered European software group that builds ERP and project-management software for the skilled trades. Formed as a buy-and-build platform, Craftview operates a portfolio of long-established regional ERP brands — C'FLUIDE, ES2000, EXTRABAT, GILDE, KS21, MOSER, OSD, PLENION, RITA BOSSE and WINWORKER — serving green industries, construction-related trades, technical services and specialized crafts across Germany, Belgium, the Netherlands and France.

- Website: https://www.craftview.de/en/
- Scale: 25,000+ active customers, 330+ employees, 11 locations, 41 key European regions
- Backed by: battery-ventures

## API surface

Craftview publishes **no public API surface** as of 2026-07-20 — no developer portal, API reference, OpenAPI/AsyncAPI definition, SDK, CLI, MCP server, sandbox, changelog, or status page was found on the corporate site or on the brand sites (winworker.de, es2000.de, plenion.be, extrabat.com, osd.de, ks21.de). No `/.well-known/` discovery documents are served.

A live but entirely undocumented JSON API host exists for the EXTRABAT brand at `api.extrabat.com` (Symfony routing error at root). It has no published documentation or definition and is therefore recorded as an observation in `well-known/` rather than catalogued as an API.

## Artifacts

- `security/craftview-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC
- `well-known/craftview-well-known.yml` — probed `/.well-known/` discovery surface (all 404)
- `llms/craftview-llms.txt` — generated llms.txt for the company
