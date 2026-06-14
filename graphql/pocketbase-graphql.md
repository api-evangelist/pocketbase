# PocketBase GraphQL API

PocketBase is a REST-only backend-as-a-service. It does not provide a native GraphQL API. All data operations are performed through a REST-ish HTTP API served at `{your-instance}/api/`, with endpoints organized around collections and records. PocketBase exposes CRUD operations, batch writes, filtering, sorting, pagination, relation expansion, and multipart file uploads entirely via REST conventions. Real-time updates are delivered through Server-Sent Events (SSE) rather than GraphQL subscriptions.

Authentication in PocketBase is also REST-based and supports password credentials, OAuth2 providers, one-time passwords (OTP), and token refresh, all via POST endpoints under `/api/collections/{collectionIdOrName}/auth-*`. There is no GraphQL endpoint, no introspection endpoint, and no plans for native GraphQL support in the official PocketBase project. Community third-party integrations may wrap PocketBase's REST API to expose a GraphQL interface, but these are not officially maintained.

The schema file accompanying this document (`pocketbase-schema.graphql`) is a documentation-only SDL representation of PocketBase's core data model types — Record, Collection, AuthRecord, and FileField — derived from the Go source code at `github.com/pocketbase/pocketbase/core`. It is intended to convey the shape of the data model for reference purposes only and cannot be used with a live GraphQL endpoint.

**Endpoint:** N/A — PocketBase does not expose a GraphQL endpoint

**Documentation:** https://pocketbase.io/docs/

**References:**
- Documentation: https://pocketbase.io/docs/
- GettingStarted: https://pocketbase.io/docs/
- API Records: https://pocketbase.io/docs/api-records/
- API Realtime: https://pocketbase.io/docs/api-realtime/
- API Files: https://pocketbase.io/docs/api-files/
- GitHub Source: https://github.com/pocketbase/pocketbase
