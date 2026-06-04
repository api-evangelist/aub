# American University of Beirut (aub)

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
