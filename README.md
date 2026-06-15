# Heap (heap)

Heap is a digital analytics platform that automatically captures every user interaction on web and mobile applications without requiring manual event tracking code. It provides product analytics, session replay, and behavioral data science capabilities to help teams understand user behavior and improve digital experiences.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/heap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/heap/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics
- Autocapture
- Digital Analytics
- Product Analytics
- Session Replay
- User Behavior

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-30

## APIs

### Heap Server-Side API

The Heap Server-Side API allows developers to send track, identify, and add user properties events to Heap from backend servers. It supports sending custom events and user properties that cannot be captured through Heap's automatic client-side tracking, such as server-side transactions, subscription changes, and backend process completions.

- **Human URL:** [https://developers.heap.io/reference/server-side-apis-overview](https://developers.heap.io/reference/server-side-apis-overview)

#### Tags

- Analytics
- Events
- Server-Side
- Tracking

#### Properties

- [Documentation](https://developers.heap.io/reference/server-side-apis-overview)
- [Getting Started](https://developers.heap.io/docs/getting-started)
- [Postman Collection](collections/heap-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/heap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Heap Track API

The Heap Track API enables developers to send custom track events from server-side applications to Heap. Each event includes an identity, event name, and optional properties. This API is used to capture important backend events such as purchases, subscription upgrades, or other server-side actions that supplement Heap's automatic client-side tracking.

- **Human URL:** [https://developers.heap.io/reference/track-1](https://developers.heap.io/reference/track-1)

#### Tags

- Analytics
- Events
- Tracking

#### Properties

- [Documentation](https://developers.heap.io/reference/track-1)
- [Postman Collection](collections/heap-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/heap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Heap Identify API

The Heap Identify API allows developers to associate a user identity with Heap's automatically captured data from the server side. This enables linking anonymous user sessions to known user identities when authentication or identification occurs on the backend rather than the client side.

- **Human URL:** [https://developers.heap.io/reference/identify-1](https://developers.heap.io/reference/identify-1)

#### Tags

- Analytics
- Identity
- Users

#### Properties

- [Documentation](https://developers.heap.io/reference/identify-1)
- [Postman Collection](collections/heap-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/heap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Heap Add User Properties API

The Heap Add User Properties API enables developers to attach custom properties to user profiles from server-side applications. These properties can include attributes such as subscription tier, account type, company name, or any other user-level data that enriches Heap's behavioral analytics and segmentation capabilities.

- **Human URL:** [https://developers.heap.io/reference/add-user-properties-1](https://developers.heap.io/reference/add-user-properties-1)

#### Tags

- Analytics
- Properties
- Users

#### Properties

- [Documentation](https://developers.heap.io/reference/add-user-properties-1)
- [Postman Collection](collections/heap-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/heap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Heap Add Account Properties API

The Heap Add Account Properties API allows developers to attach custom properties to account-level profiles from server-side applications. This is used for B2B analytics scenarios where users belong to organizations or accounts, enabling analysis at the account level in addition to the individual user level.

- **Human URL:** [https://developers.heap.io/reference/add-account-properties-1](https://developers.heap.io/reference/add-account-properties-1)

#### Tags

- Accounts
- Analytics
- B2B
- Properties

#### Properties

- [Documentation](https://developers.heap.io/reference/add-account-properties-1)
- [Postman Collection](collections/heap-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/heap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Heap Partner Webhooks (Data-out API)

Heap's partner webhook surface (also called the Data-out API) delivers behavioral segment membership deltas to partner-hosted HTTPS endpoints. The documented action type is segment.users.sync, which sends adds and removes for a Heap segment on a roughly four-hour cadence. Requests are signed with a Heap-Hash header containing a timestamp and HMAC-SHA256 of the body using a shared webhook secret key, and partners are expected to verify the signature and respond 200 OK to avoid retries.

- **Human URL:** [https://developers.heap.io/docs/creating-a-new-heap-integration-partners](https://developers.heap.io/docs/creating-a-new-heap-integration-partners)

#### Tags

- Analytics
- Segments
- Webhooks

#### Properties

- [Documentation](https://developers.heap.io/docs/creating-a-new-heap-integration-partners)
- [Reference](https://github.com/heap/heap-partner-api-reference)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/heap/refs/heads/main/openapi/heap-webhooks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/heap-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/heap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/heap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/heap)
- [LinkedIn](https://www.linkedin.com/company/heap-inc-)
- [Website](https://www.heap.io)
- [Documentation](https://developers.heap.io)
- [Getting Started](https://developers.heap.io/docs/getting-started)
- [Authentication](https://developers.heap.io/reference/authentication)
- [Blog](https://www.heap.io/blog)
- [Pricing](https://www.heap.io/pricing)
- [Login](https://heapanalytics.com/app/login)
- [Sign Up](https://heapanalytics.com/signup)
- [Support](https://help.heap.io)
- [Terms of Service](https://www.heap.io/terms-of-service)
- [Privacy Policy](https://www.heap.io/privacy-policy)
- [Status Page](https://status.heap.io)
- [Features](undefined)
- [Integrations](https://www.heap.io/partners)
- [L L Ms Txt](https://developers.heap.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
