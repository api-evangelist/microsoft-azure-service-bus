# Azure Service Bus (microsoft-azure-service-bus)

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

Azure Service Bus is a fully managed enterprise message broker with message queues and publish-subscribe topics. It enables decoupling applications and services with reliable asynchronous messaging, supporting sessions, dead-lettering, scheduled delivery, duplicate detection, and transactions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-azure-service-bus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-service-bus/refs/heads/main/apis.yml)

## Tags

- Enterprise Messaging
- Message Broker
- Messaging
- Publish Subscribe
- Queues
- Topics

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Azure Service Bus REST API

Azure Service Bus REST API provides operations for sending and receiving messages through queues and topics with support for sessions, dead-lettering, scheduled delivery, duplicate detection, and transactions.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/servicebus/](https://learn.microsoft.com/en-us/rest/api/servicebus/)
- **Base URL:** `https://{namespace}.servicebus.windows.net/`

#### Tags

- Messaging
- Queues
- Subscriptions
- Topics

#### Properties

- [OpenAPI](openapi/microsoft-azure-service-bus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-azure-service-bus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-service-bus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/servicebus/)
- [Authentication](https://learn.microsoft.com/en-us/rest/api/eventhub/authenticate-shared-access-signature)
- [Reference](https://learn.microsoft.com/en-us/rest/api/servicebus/resourceprovider)

### Azure Service Bus Management REST API

The management REST API enables namespace, queue, topic, and subscription configuration through Azure Resource Manager, including SKU, network rules, authorization rules, and disaster recovery configuration.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/servicebus/controlplane-stable/](https://learn.microsoft.com/en-us/rest/api/servicebus/controlplane-stable/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- Management
- Namespaces
- Provisioning

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/servicebus/controlplane-stable/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-flows-app-scenarios)
- [Postman Collection](collections/microsoft-azure-service-bus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-service-bus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Azure)
- [Portal](https://portal.azure.com/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/service-bus/)
- [Documentation](https://learn.microsoft.com/en-us/azure/service-bus-messaging/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-quickstart-portal)
- [S D Ks](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues)
- [Status Page](https://azure.status.microsoft/en-us/status)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://support.microsoft.com/)
- [Blog](https://azure.microsoft.com/en-us/blog/product/service-bus/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azureservicebus)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
