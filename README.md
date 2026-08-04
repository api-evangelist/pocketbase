# PocketBase (pocketbase)

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

PocketBase is an open-source backend-as-a-service delivered as a single executable, providing a REST API for managing collections, records, authentication, file uploads, real-time subscriptions via Server-Sent Events, and admin management through a built-in dashboard. It embeds SQLite for persistent storage and supports OAuth2, OTP, and password-based authentication out of the box. Developers can extend PocketBase with custom business logic using Go or JavaScript hooks and event handlers. Official SDKs for JavaScript and Dart make client integration straightforward across web, mobile, and desktop platforms.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/pocketbase/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=pocketbase-api-evangelist&utm_content=repo

---

## Tags

- Backend-as-a-Service
- Open Source
- SQLite
- Realtime
- Authentication
- File Storage
- REST API
- Self-Hosted
- Go

---

## APIs

| API | Description |
|-----|-------------|
| Records API | CRUD operations for collection records with filtering, sorting, pagination, and batch support |
| Authentication API | Password, OAuth2, OTP, token refresh, email verification, and password reset |
| Realtime API | Server-Sent Events subscriptions for real-time record change notifications |
| Files API | File download, thumbnail generation, and protected file token generation |
| Settings API | Superuser-only application configuration, S3 testing, and rate-limit management |

---

## Plans / Rate Limits / FinOps

| Resource | Location |
|----------|----------|
| Plans & Pricing | [plans/pocketbase-plans-pricing.yml](plans/pocketbase-plans-pricing.yml) |
| Rate Limits | [rate-limits/pocketbase-rate-limits.yml](rate-limits/pocketbase-rate-limits.yml) |
| FinOps | [finops/pocketbase-finops.yml](finops/pocketbase-finops.yml) |

**Pricing summary:** PocketBase is MIT-licensed and entirely free. Self-hosters pay only for their own infrastructure (VPS, storage, bandwidth). No hosted SaaS tiers exist from the project.

**Rate limits (configurable defaults):**
- Auth endpoints: 2 requests / 3 seconds
- Record create: 20 requests / 5 seconds
- Batch API: 3 requests / 1 second
- General API: 300 requests / 10 seconds

**FinOps range:** $0/month (Oracle Free Tier) to $20–$100+/month for production workloads.

---

## Timestamps

| Field | Value |
|-------|-------|
| Created | 2026-06-12 |
| Modified | 2026-06-12 |

---

## Common

| Type | URL |
|------|-----|
| Website | https://pocketbase.io |
| Documentation | https://pocketbase.io/docs/ |
| GitHub Org | https://github.com/pocketbase |
| Blog / Releases | https://github.com/pocketbase/pocketbase/releases |
| Pricing / FAQ | https://pocketbase.io/faq/ |
| X (Twitter) | https://x.com/pocketbase |

---

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
