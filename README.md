# Akur8 (akur8)

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

Akur8 is a cloud-based actuarial AI platform for P&C and life insurers, covering pricing (Data, Risk, Demand, Rate, Rate Repo, Optim, Discover), reserving, and production deployment of rating models. There is no self-serve public developer API or public API reference published on akur8.com; the platform is sold and onboarded as enterprise SaaS through a sales-led, typically two-week free pilot. The one confirmed API capability is Akur8 Deploy - once a pricing model built in Akur8 Rate is finalized, Deploy auto-generates a private, tenant-specific real-time REST rating/scoring endpoint that a customer's own policy admin or quoting system calls at quote time to return a price in milliseconds. Access to that generated endpoint is provisioned per customer within a paid contract, not published for anonymous developer signup; rating tables can also be exported in CSV, JSON, PMML, and POJO formats for offline integration.

**Access model:** Gated / enterprise-provisioned. No public developer portal, no `api.akur8.com` or `docs.akur8.com`, no self-serve API keys. See [review.yml](review.yml) for the full findings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/akur8/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/akur8/refs/heads/main/apis.yml)

## Tags

- Insurance
- Insurtech
- Actuarial
- Pricing
- GLM
- Rating Engine

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Akur8 Deploy Rating API

Akur8 Deploy auto-generates a real-time REST rating endpoint from a finalized pricing model built in Akur8 Rate. A customer's policy admin system or quoting engine calls the generated endpoint to score/rate a risk and receive a price in milliseconds. The endpoint is provisioned per customer, per deployed model, inside a paid Akur8 contract - there is no fixed public base URL, no self-serve signup, and no published API reference. Rating tables can also be exported in CSV, JSON, PMML, and POJO formats as a non-API integration path.

*This API is modeled from publicly available marketing/FAQ language only (`endpointsModeled: true`); no endpoint paths, base URL, or request/response schema are published by Akur8.*

- **Human URL:** [https://www.akur8.com/pricing/deploy](https://www.akur8.com/pricing/deploy)

#### Tags

- Rating
- Scoring
- Real-Time
- Deploy

#### Properties

- [Documentation](https://www.akur8.com/pricing/deploy)
- [Documentation](https://www.akur8.com/resources/faq)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/akur8)
- [Website](https://www.akur8.com/)
- [Plans](plans/akur8-plans-pricing.yml)
- [Fin Ops](finops/akur8-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
