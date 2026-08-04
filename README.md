# Universiti Teknologi PETRONAS (universiti-teknologi-petronas)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
