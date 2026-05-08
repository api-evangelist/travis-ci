# Travis CI (travis-ci)

Travis CI is a hosted continuous integration service supporting GitHub, GitLab and Bitbucket. Two REST APIs are exposed: the legacy v2/v2.1 (deprecated) and the current v3 (powers the Travis web UI). Travis CI is also offered as Server for on-prem / private-cloud deployments.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **REST v3** — `https://api.travis-ci.com` — current API; 50+ resource types covering builds, jobs, repositories, users, organizations, crons, caches, env vars, requests, config validation. [Docs](https://developer.travis-ci.com/) · [API Explorer](https://developer.travis-ci.com/explore/).
- **REST v2.1 (deprecated)** — `https://api.travis-ci.com` with `Accept: application/vnd.travis-ci.2.1+json`. [Docs](https://docs.travis-ci.com/api/).

## OpenAPI
Travis CI does not publish an OpenAPI/Swagger document for either v2.1 or v3 as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`.

## Tags
DevOps, CI/CD, Build, Open Source, Hosted, GitHub

## Common Properties
- [Website](https://www.travis-ci.com/) · [Docs](https://docs.travis-ci.com/) · [Pricing](https://www.travis-ci.com/pricing/)
- [GitHub](https://github.com/travis-ci) · [Status](https://www.traviscistatus.com/)
- [Plans](plans/travis-ci-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/travis-ci-rate-limits.yml) — reconciled (concurrency + credit budgets; per-second numeric API quota not public)
- [FinOps](finops/travis-ci-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Open Source** — free for OSS repos with credit allotment.
- **Usage Based** — $15/mo (or $13.75/mo annual). 35K credits/mo (or 420K/yr), 80 concurrent jobs.
- **Unlimited** — $78+/mo (or $72+/mo annual). Unlimited credits, up to 300 concurrent jobs.
- **Server** — $34/mo on-prem / private-cloud; supports Perforce / SVN.
- Volume discounts at 20+ users; custom enterprise pricing available.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
