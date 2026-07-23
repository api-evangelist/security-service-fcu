# Security Service Federal Credit Union (security-service-fcu)

Security Service Federal Credit Union (SSFCU) is a member-owned, not-for-profit financial cooperative headquartered in San Antonio, Texas, federally chartered and insured by the National Credit Union Administration (NCUA). It is one of the largest credit unions in the United States, serving members across Texas, Colorado, and Utah with consumer and business banking, deposit accounts, credit cards, auto and mortgage lending, and investment services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/security-service-fcu/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/security-service-fcu/refs/heads/main/apis.yml)

## Open-Finance & API Posture

SSFCU exposes **no first-party public developer API**. There is no developer portal — `developer.ssfcu.org`, `developers.ssfcu.org`, and `api.ssfcu.org` do not resolve, and no `/developers`, `/developer`, or `/api` path exists on the main site (all return HTTP 404). No downloadable OpenAPI/Swagger specification is published.

This is the ordinary posture for a US credit union. US open finance is voluntary and fragmented — there is no single mandated open-banking contract. SSFCU publishes no documented FDX (Financial Data Exchange) participation and no stated CFPB Section 1033 (Personal Financial Data Rights) data-access API. Any API capability is delivered through its core banking provider rather than a self-serve developer program, and consumer-permissioned account data is reachable only indirectly through third-party aggregators (e.g. Plaid, MX, Finicity, Akoya) rather than a first-party API surface.

This record is therefore identity-only: an honest profile of the institution with no public API to catalog.

## Tags

- Financial Services
- Banking
- United States
- Credit Union
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Security Service FCU does not publish a public developer API.

## Common Properties

- [Website](https://ssfcu.org/)
- [Support](https://ssfcu.org/contact-us)
- [Terms of Service](https://ssfcu.org/enrollment/terms-conditions)
- [Privacy Policy](https://ssfcu.org/account-services/disclosures-and-terms#privacy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
