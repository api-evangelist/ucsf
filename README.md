# University of California, San Francisco (ucsf)

The University of California, San Francisco (UCSF) is a public health-sciences university dedicated exclusively to graduate and health professions education, biomedical research, and patient care, ranked #39 in the QS World University Rankings 2025. This repository catalogs UCSF's public developer and API footprint as an [APIs.json](http://apisjson.org/) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucsf/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucsf-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Health Sciences, Research, Researcher Profiles, Open Data, United States

## APIs

- **UCSF Profiles JSON API** — Open JSON API (v2) for 8,000+ UCSF researchers, faculty, and postdocs (publications, grants, ORCID, research interests). Live and publicly consumable with a required `source` parameter; CORS/JSONP supported. Base URL: `https://api.profiles.ucsf.edu/json/v2/`. Docs: https://profilesdeveloper.ucsf.edu/json-api
- **Developer@UCSF API Portal (internal)** — Institutional API catalog on MuleSoft Anypoint (SIS Course Enrollment, Building Metadata, ServiceNow, CV/Advance). Gated behind MyAccess SSO and the campus network; not publicly consumable. Docs: https://developer.ucsf.edu/all-apis

## Plans

See [plans/ucsf-plans-pricing.yml](plans/ucsf-plans-pricing.yml).

## Rate Limits

See [rate-limits/ucsf-rate-limits.yml](rate-limits/ucsf-rate-limits.yml).

## FinOps

See [finops/ucsf-finops.yml](finops/ucsf-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ucsf.edu/
- GitHub: https://github.com/UCSF
- LinkedIn: https://www.linkedin.com/school/ucsf/
- Developer Portal: https://developer.ucsf.edu/
- Plans: plans/ucsf-plans-pricing.yml
- Rate Limits: rate-limits/ucsf-rate-limits.yml
- FinOps: finops/ucsf-finops.yml
- Review: review.yml

## Notes

Only the UCSF Profiles JSON API was verified as a public, documented, live API (it returned real JSON when probed). The Developer@UCSF / Integration Services MuleSoft portal and its APIs (SIS, building metadata, ServiceNow, CV) exist and are publicly indexed but are gated behind MyAccess SSO and the UCSF network/VPN and were not reachable from the review network; they are cataloged for completeness, not as public endpoints. The data.ucsf.edu portal is a data catalog (Scuba ecosystem) with no documented public open-data API. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
