# Akur8 (akur8)

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
