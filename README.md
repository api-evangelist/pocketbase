# PocketBase (pocketbase)

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
