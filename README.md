# Travis CI (travis-ci)

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

Travis CI is a hosted continuous integration service supporting GitHub, GitLab and Bitbucket. Two REST APIs are available: the legacy v2/v2.1 API (deprecated) and the current v3 API used by the web UI. Travis CI is also available as Enterprise (on-premises) and Server (private cloud).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/travis-ci/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/travis-ci/refs/heads/main/apis.yml)

## Tags

- DevOps
- CI/CD
- Build
- Open Source
- Hosted
- GitHub

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Travis CI REST API v3

Current REST API used by the Travis CI web UI. 50+ resource types covering builds, jobs, repositories, users, organizations, crons, caches, environment variables, requests and config validation. Hypermedia, eager/partial loading and pagination supported. Token-based auth obtained via GitHub OAuth.

- **Human URL:** [https://developer.travis-ci.com/](https://developer.travis-ci.com/)
- **Base URL:** `https://api.travis-ci.com`

#### Tags

- REST
- v3
- Builds
- Jobs
- Repos

#### Properties

- [Documentation](https://developer.travis-ci.com/)
- [A P I Explorer](https://developer.travis-ci.com/explore/)
- [Authentication](https://developer.travis-ci.com/authentication)
- [Postman Collection](collections/travis-ci.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travis-ci.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Travis CI REST API v2.1 (deprecated)

Legacy v2/v2.1 REST API; superseded by v3 but still in use. Builds, jobs, branches, logs, env vars, caches, SSH keys, requests. Authenticated via Bearer access tokens exchanged with GitHub.

- **Human URL:** [https://docs.travis-ci.com/api/](https://docs.travis-ci.com/api/)
- **Base URL:** `https://api.travis-ci.com`

#### Tags

- REST
- v2.1
- Deprecated
- Builds

#### Properties

- [Documentation](https://docs.travis-ci.com/api/)
- [Deprecation Notice](https://blog.travis-ci.com/2018-01-22-api-v2.1-deprecation)
- [Postman Collection](collections/travis-ci.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travis-ci.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/travis-ci)
- [Website](https://www.travis-ci.com/)
- [Documentation](https://docs.travis-ci.com/)
- [Pricing](https://www.travis-ci.com/pricing/)
- [Git Hub](https://github.com/travis-ci)
- [Status Page](https://www.traviscistatus.com/)
- [Plans](plans/travis-ci-plans-pricing.yml)
- [Rate Limits](rate-limits/travis-ci-rate-limits.yml)
- [Fin Ops](finops/travis-ci-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
