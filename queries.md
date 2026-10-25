# Queries — 2026-10-25

Run before any claim. Strings are the ones actually sent.

## Notion

- Fetch database `https://app.notion.com/p/3faa8c90704a4e0f81435cb10ca155b2`. Data source `collection://382d9c24-c10c-4fbf-9628-c7be3a1e4007`.
- SQL: latest 12 rows by Timestamp. Newest hit: `CLOSED-2026-10-24 Kind-Overshoot not minted`.
- Fetch High-Agency Execution Partner `3d74e96f134c817e8b15f6fbf8cb5dd1` (edited 2026-10-23).
- Fetch Skill Creator — Notion MCP `3d74e96f134c818b8968c25224da1942` (edited 2026-10-23).
- Search: `high-agency execution partner adversarial pass skill-creator discovery protocol`.

## GitHub

- `github___get_me` → login `sENZ5hFx`, name Haley Bird.
- File read `sENZ5hFx/substrate-export-class-2026-09-30` `skills/high-agency-partner/SKILL.md` (rule 7).
- Tree and file reads under `sENZ5hFx/realm-discovery-engine-outputs`, including `sessions/2026-10-24-kind-overshoot-bytes-still-missing/SESSION.md` and `queries.md`.
- `GET https://api.github.com/repos/steviewalker/CMIP6_POC_flux_comparison/commits?per_page=3` → HEAD `b32dddf4b87d7da6cee37897df6b305ec4c748a0` (2025-05-07). Unchanged. Non-specimen.

## Live web and APIs

- Unpaywall `https://api.unpaywall.org/v2/10.1029/2024GB008329?email=heyhaleybird@gmail.com` → is_oa true; only pdfdirect URL.
- OpenAlex `https://api.openalex.org/works/https://doi.org/10.1029/2024GB008329` → any_repository_has_fulltext false.
- Crossref `https://api.crossref.org/works/10.1029/2024GB008329` → CC-BY 4.0 from 2025-04-19. Similarity-checking link is the Wiley pdf URL.
- Europe PMC `DOI:10.1029/2024GB008329` → hitCount 0.
- Zenodo `doi:10.1029/2024GB008329` → hits 0.
- OpenAIRE `doi=10.1029/2024GB008329` → Wiley DOI and ESSOA DOI only.
- Semantic Scholar graph `DOI:10.1029/2024GB008329` → HTTP 429.
- CORE v3 `q=doi:10.1029/2024GB008329` → HTTP 200, `totalHits` 0. Unauthenticated. 2026-10-24 was HTTP 429.
- Fatcat lookup → timeout. Not a zero-hit.
- Internet Archive advanced search → `BACKEND_ERROR`. Not a zero-hit.
- ADS `doi:10.1029/2024GB008329` → HTTP 401. Not a zero-hit.
- GET `https://onlinelibrary.wiley.com/doi/pdfdirect/10.1029/2024GB008329` → 403, cf-ray `a50305a99ce725d1-IAD`, HTML SHA-256 `329760186f19f6fd3143fe29ba08a6b5fb05ecbd5d4a52564da68985520b9f24`.
- GET ResearchGate publication `390940892` → 403, cf-ray `a50305a91db09393-IAD`, HTML SHA-256 `494313d766ae884814e3f7118605e457e02bfece3d1484abf686b6b582e5b7ec`.
- GET `https://www.hilarypalevsky.com/publications` → 200. Preprint href still user `816446` article `1217154`.
- Boston College Primo `q=any,contains,2024GB008329` → 1 PC hit; free link is Unpaywall pdfdirect; local results 0.
- Web search: `Walker Palevsky 10.1029/2024GB008329 PDF` and the CMIP6 export-flux title. ResearchGate and Wiley are indexed. No new file host.

## Refused

- Sci-hub and any Cloudflare challenge solver.
- Scoring the search-index excerpt of 4.9–8.3 Pg C/yr.
- One invented discovery per realm cell.
- A new skill page.
- Extending `structural-gap-atlas`.
