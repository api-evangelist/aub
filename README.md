# American University of Beirut (aub)

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

The American University of Beirut (AUB) is a private research university in Beirut, Lebanon, founded in 1866 and ranked #250 in the QS World University Rankings 2025. This repository catalogs AUB's public, machine-readable developer/API footprint as an [APIs.json](https://apisjson.org) provider profile. AUB has no centralized developer portal; its public APIs are centered on the University Libraries' ScholarWorks repository (DSpace 9.1) and a Shibboleth SAML identity provider.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/aub/refs/heads/main/apis.yml
- Naftiko Run: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=aub-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Lebanon, Middle East, Research, Libraries, Open Access

## APIs

- **AUB ScholarWorks DSpace REST API** — Public HAL/JSON REST API for the institutional repository on DSpace 9.1. Base: `https://scholarworks.aub.edu.lb/server/api`. Docs: [LibGuide](https://aub.edu.lb.libguides.com/AUB-Scholarworks), [DSpace REST API](https://wiki.lyrasis.org/display/DSDOC9x/REST+API)
- **AUB ScholarWorks OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint. Base: `https://scholarworks.aub.edu.lb/server/oai/request`. Docs: [LibGuide](https://aub.edu.lb.libguides.com/AUB-Scholarworks)
- **AUB Shibboleth Identity Provider (SAML 2.0)** — Institutional SSO identity provider with published SAML metadata. Endpoint: `https://idp.aub.edu.lb/idp/shibboleth`. Docs: [Service Desk](https://servicedesk.aub.edu.lb/TDClient/Requests/ServiceDet?ID=30424)

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/aub-plans-pricing.yml](plans/aub-plans-pricing.yml)
- Rate Limits: [rate-limits/aub-rate-limits.yml](rate-limits/aub-rate-limits.yml)
- FinOps: [finops/aub-finops.yml](finops/aub-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.aub.edu.lb/
- GitHub: https://github.com/AUB-CMPS
- LinkedIn: https://www.linkedin.com/school/american-university-of-beirut
- Authentication: https://idp.aub.edu.lb/idp/shibboleth
- Review: [review.yml](review.yml)

## Notes

All endpoints were probed live on 2026-06-03. The ScholarWorks REST root (`/server/api`) and OAI-PMH endpoint (`/server/oai/request`) both returned HTTP 200 and self-identify as repository "AUB ScholarWorks" on DSpace 9.1. The Shibboleth IdP metadata endpoint returned a valid SAML EntityDescriptor. Legacy DSpace paths (`/oai/request`, `/rest/`) return 404, consistent with DSpace 7+ moving these under `/server`. No private/SSO-gated systems (SIS, service desk) are cataloged as APIs since they are not publicly documented. No endpoints were fabricated. The `AUB-CMPS` GitHub org reflects the Computer Science department's course/community code, not an official institutional API program.

## Maintainers

- Kin Lane — kin@apievangelist.com
