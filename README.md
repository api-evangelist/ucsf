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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of California, San Francisco (UCSF) is a public health-sciences university dedicated exclusively to graduate and health professions education, biomedical research, and patient care. This repository catalogs UCSF's public developer and API footprint as an [APIs.json](http://apisjson.org/) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucsf/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucsf-api-evangelist&utm_content=repo

## Type

University / Public Research University / Producer / Public

## Who operates what

A university is a federation of buyers, so every surface below carries an **operator**. `institution` means UCSF runs the thing itself. `tenant` means the data is UCSF's but the contract belongs to a platform vendor, and the vendor's spec is deliberately **not** saved here.

### Institution-operated

- **UCSF Profiles JSON API** — `https://api.profiles.ucsf.edu/json/v2/` — open JSON API (v2) over UCSF Profiles, run by UCSF CTSI, covering 8,000+ researchers, faculty and postdocs with ORCID iDs, publications, clinical trials, and funding. Anonymous; a `source` parameter identifies the caller but is not a credential. CORS and JSONP. Deprecation notices travel in-band via an `api_notes` field. Docs: https://profilesdeveloper.ucsf.edu/json-api
- **UCSF Industry Documents Library Solr API** — `https://solr.idl.ucsf.edu/solr/ltdl3/` — anonymous Apache Solr query interface over **28,298,987** internal documents from the tobacco, drug, chemical, food, fossil fuel and opioid industries, produced in litigation and preserved by the UCSF Library Center for Knowledge Management. Responses in xml, json, python, ruby, php or csv.
- **UCSF Identity Provider (Shibboleth / InCommon)** — `https://dp.ucsf.edu/idp/shibboleth` — UCSF self-publishes SAML 2.0 metadata on its own host (entityIDs `urn:mace:incommon:ucsf.edu` and `https://dp.ucsf.edu/idp/shibboleth`, `shibmd:Scope ucsf.edu`, with an IDPSSODescriptor, an AttributeAuthorityDescriptor and an SPSSODescriptor). InCommon redistributes a signed copy through its MDQ service and re-exports to eduGAIN.
- **UCSF Industry Documents Library Content API** — `https://cms.libckm.org/api/` — publicly readable REST content layer behind the IDL website, 320 editorial pages. Undocumented and unversioned; recorded, but no contract is claimed for it.

### Tenant relationships (UCSF's data, a vendor's contract)

- **UCSF DataShare** — https://datashare.ucsf.edu/ — Dryad platform. 1,306 DataCite DOIs carry a UCSF publisher string.
- **eScholarship OAI-PMH set `ucsf`** — California Digital Library, UC-system-wide.
- **UCSF Library Discovery** — https://search.library.ucsf.edu/ — Ex Libris Primo.
- **UCSF Course Catalog** — https://coursecatalog.ucsf.edu/ — Leepfrog CourseLeaf. No course or registrar API is exposed.

## What UCSF does not publish

No OpenAPI. No changelog or release feed for either API. No status feed. No scopes — both public APIs are anonymous and undifferentiated. No machine-readable error contract. No public course, timetable or registrar API. **No central developer portal**: the `developer.ucsf.edu` host recorded in the June 2026 profile returns NXDOMAIN from Google, Cloudflare and Quad9 and has zero Internet Archive snapshots at any date, so it was never publicly reachable and all pointers to it have been removed. UCSF's live gateway is `unified-api.ucsf.edu`, which answers only with a Citrix NetScaler challenge.

## Education-regime standard conformance

| Standard | Status | Operator |
|---|---|---|
| `saml` | conformant | institution |
| `shibboleth` | conformant | institution |
| `orcid` | conformant | institution |
| `oai-pmh` | conformant | tenant (California Digital Library) |
| `datacite` | conformant | tenant (Dryad) |
| `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti`, `crossref` | not found | — |

See [conformance/ucsf-education-standards-conformance.yml](conformance/ucsf-education-standards-conformance.yml).

## Known defect in a UCSF-operated API

The IDL Solr `rows` parameter is accepted and echoed back in `responseHeader.params` but **not honoured** — `rows=0`, `rows=1`, `rows=5` and `rows=100` each returned 1000 documents on 2026-08-19. UCSF's published documentation states "we only return 100 records at a time" and instructs paging with `&start=100`; the deployed page size is 1000. `start` is honoured. Recorded in [lifecycle/ucsf-lifecycle.yml](lifecycle/ucsf-lifecycle.yml).

## Artifacts

| Artifact | Path |
|---|---|
| OpenAPI (derived) | [openapi/](openapi/) — pristine copies in [openapi/_original/](openapi/_original/) |
| JSON Schema | [json-schema/](json-schema/) |
| Examples (live captures) | [examples/](examples/) |
| Vocabulary | [vocabulary/ucsf-vocabulary.yml](vocabulary/ucsf-vocabulary.yml) |
| Authentication + SAML metadata | [authentication/](authentication/) |
| Scopes | [scopes/ucsf-scopes.yml](scopes/ucsf-scopes.yml) |
| Errors | [errors/ucsf-errors.yml](errors/ucsf-errors.yml) |
| Conformance | [conformance/](conformance/) |
| Lifecycle | [lifecycle/ucsf-lifecycle.yml](lifecycle/ucsf-lifecycle.yml) |
| Governance rules | [rules/ucsf-governance-rules.yml](rules/ucsf-governance-rules.yml) |
| JSON-LD | [json-ld/](json-ld/) |
| Plans / Rate limits / FinOps | [plans/](plans/) · [rate-limits/](rate-limits/) · [finops/](finops/) |
| Review log | [review.yml](review.yml) |

Every artifact carries `generated`, `method` (`searched` / `generated` / `derived` / `probed` / `none`) and `source`. The OpenAPI descriptions are **derived by API Evangelist** from UCSF's own documentation plus live probed responses — UCSF publishes no OpenAPI of its own.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Maintainers

- Kin Lane — kin@apievangelist.com
