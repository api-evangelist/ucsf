# University of California, San Francisco (ucsf)

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
