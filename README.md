# Universiti Teknologi PETRONAS (universiti-teknologi-petronas)

Universiti Teknologi PETRONAS (UTP) is a leading private research university in Seri Iskandar, Perak, Malaysia, established in 1997 and wholly owned by PETRONAS. It is ranked #270 in the QS World University Rankings 2025. This repository catalogs UTP's confirmed public developer/API footprint as an APIs.json index.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/universiti-teknologi-petronas/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=universiti-teknologi-petronas-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Institutional Repository, OAI-PMH, Malaysia

## APIs

- **UTPedia Institutional Repository (OAI-PMH)** — EPrints 3.4.7 OAI-PMH 2.0 endpoint for harvesting repository metadata (oai_dc, mets, didl, rdf, oai_bibl, uketd_dc).
  - Repository: http://utpedia.utp.edu.my/
  - Documentation (Identify): http://utpedia.utp.edu.my/cgi/oai2?verb=Identify
  - Base URL: http://utpedia.utp.edu.my/cgi/oai2

## Plans / Rate Limits / FinOps

- Plans: [plans/universiti-teknologi-petronas-plans-pricing.yml](plans/universiti-teknologi-petronas-plans-pricing.yml)
- Rate Limits: [rate-limits/universiti-teknologi-petronas-rate-limits.yml](rate-limits/universiti-teknologi-petronas-rate-limits.yml)
- FinOps: [finops/universiti-teknologi-petronas-finops.yml](finops/universiti-teknologi-petronas-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.utp.edu.my/
- LinkedIn: https://www.linkedin.com/school/universiti-teknologi-petronas/
- Authentication (SSO): https://ucs.utp.edu.my/SignIn
- Review: [review.yml](review.yml)

## Notes

- No dedicated developer portal or documented REST/GraphQL APIs were found for UTP.
- The only confirmed public, machine-readable API is the UTPedia OAI-PMH endpoint, verified via a valid Identify response.
- No official UTP GitHub organization was confirmed; results surfaced only student-club accounts (e.g., CYBERHAX UTP, UTPHAX), which are not included here.
- The UCS single sign-on portal is authentication-gated and is listed for reference, not as a public API.
- No endpoints were invented; only URLs actually probed are cataloged. See review.yml for per-URL status.

## Maintainers

- Kin Lane — kin@apievangelist.com
