# American University of Beirut

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

The American University of Beirut is a private, non-profit research university in Beirut, Lebanon, chartered in New York State and founded in 1866. AUB publishes no developer portal, no API gateway and no institution-authored API contract of any kind — every machine-readable surface it operates is a standards-based deployment of third-party software running on AUB's own hosts, and that distinction is the whole of this profile. Four such surfaces were verified live on 2026-09-01. AUB ScholarWorks (scholarworks.aub.edu.lb) is an AUB-hosted DSpace 9.1 institutional repository holding 24,318 items across 25 communities, serving an anonymous HAL/JSON REST API and an OAI-PMH 2.0 endpoint with thirteen metadata formats. AUB runs its own Shibboleth SAML 2.0 identity provider at idp.aub.edu.lb, scoped aub.edu.lb, and — the strongest institution-operated surface it has — that IdP is registered in InCommon and resolvable through the InCommon MDQ service with the REFEDS Sirtfi entity category asserted. AUB's learning management system is an AUB-hosted Moodle at lms.aub.edu.lb whose Web Services REST endpoint answers anonymously with a structured invalidtoken error and whose LTI 1.3 platform JWKS and token endpoints are publicly reachable. AUB is a Crossref member (id 13566, prefix 10.63014), holds Handle prefix 10938 and is registered in ROR as 04pznsd21. Its library discovery and management stack (Ex Libris Primo and Alma), its LibGuides estate (Springshare, site 4901) and its Ellucian Banner student information system are vendor tenancies recorded here as relationships, with no vendor contract saved under AUB's name.

**Areas:** University · Higher Education · Education · Lebanon · Middle East · Private Research University · Research · Research Data · Open Access · Library · Institutional Repository · Identity Federation

## American University of Beirut on APIs.io

Everything profiled for American University of Beirut is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/aub/](https://apis.io/providers/aub/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [AUB ScholarWorks DSpace REST API](https://apis.io/apis/aub/scholarworks-rest/) — Anonymous HAL/JSON REST API for AUB ScholarWorks, AUB's institutional repository, running DSpace 9.1 on AUB's own host. The service root self-describes as…
- [AUB ScholarWorks OAI-PMH](https://apis.io/apis/aub/scholarworks-oai/) — OAI-PMH 2.0 metadata harvesting endpoint for AUB ScholarWorks. Identify returns repositoryName "AUB ScholarWorks", repositoryIdentifier…
- [AUB Shibboleth Identity Provider (SAML 2.0)](https://apis.io/apis/aub/shibboleth-idp/) — AUB's own Shibboleth SAML 2.0 identity provider, the front door to campus single sign-on. The metadata endpoint serves a signed EntityDescriptor with…
- [InCommon federation registration (AUB IdP)](https://apis.io/apis/aub/incommon-federation/) — AUB's identity provider is registered in InCommon, the United States research and education identity federation, and is resolvable through the InCommon…
- [AUB Moodle Web Services (REST)](https://apis.io/apis/aub/moodle-webservices/) — AUB's learning management system is a Moodle instance the university hosts itself at lms.aub.edu.lb (moodle.aub.edu.lb is a CNAME to it), fronted by an AWS…
- [AUB Moodle LTI 1.3 platform endpoints](https://apis.io/apis/aub/moodle-lti-platform/) — AUB's Moodle is configured as an IMS Global LTI 1.3 / LTI Advantage platform, and two of its platform endpoints are publicly reachable without credentials.…
- [Crossref membership (AUB)](https://apis.io/apis/aub/crossref-member/) — AUB is a Crossref member in its own right — member id 13566, primary name "American University of Beirut", DOI prefix 10.63014. Probed against the Crossref…
- [Handle System prefix 10938 (AUB ScholarWorks)](https://apis.io/apis/aub/handle-prefix/) — AUB holds Handle System prefix 10938, the persistent identifier namespace behind every AUB ScholarWorks record — the repository's OAI sample identifier is…
- [ROR registration (AUB)](https://apis.io/apis/aub/ror-record/) — The American University of Beirut is registered in the Research Organization Registry as https://ror.org/04pznsd21. Three related AUB entities carry their…
- [AUB Libraries discovery and management (Ex Libris Primo / Alma)](https://apis.io/apis/aub/library-discovery/) — AUB's library discovery and library services platform are Ex Libris products under AUB-specific tenancies: aub.primo.exlibrisgroup.com and…
- [AUB Libraries LibGuides (Springshare)](https://apis.io/apis/aub/libguides/) — AUB Libraries runs a Springshare LibGuides estate at aub.edu.lb.libguides.com under site_id 4901 — the guides are AUB-authored (the ScholarWorks guide, an…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Aub Context](https://apis.io/jsonld/aub/aub-context/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Aub Domain Security](https://apis.io/security/aub/aub-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Aub Plans Pricing](https://apis.io/plans/aub/aub-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Aub Rate Limits](https://apis.io/rate-limits/aub/aub-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Aub Finops](https://apis.io/finops/aub/aub-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.aub.edu.lb/)
- [Documentation](https://aub.edu.lb.libguides.com/AUB-Scholarworks)
- [Support](https://servicedesk.aub.edu.lb/TDClient/1398/Portal/Home/)
- [Privacy policy](https://www.aub.edu.lb/Pages/privacy.aspx)
- [GitHub](https://github.com/AUB-CMPS)

## API Evangelist rating

**Kin Score 21.3** — emerging · rubric 0.24.0 · scored 2026-10-20

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 14.3 |
| Contract governance | 18.2 |
| Operational transparency | 7.9 |
| Developer ergonomics | 21.4 |
| Access clarity | 15.8 |

**Agent readiness 3.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 22.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/aub/](https://apis.io/providers/aub/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for American University of Beirut: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/aub/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
