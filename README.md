# Apache ServiceMix (apache-servicemix)

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

Apache ServiceMix is a flexible, open-source integration container that unifies the features and functionality of Apache ActiveMQ, Camel, CXF, and Karaf into a powerful runtime for building enterprise integration solutions.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Enterprise Integration, ESB, Integration, Messaging, OSGi, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache ServiceMix REST API
ServiceMix provides REST endpoints for managing OSGi bundles, Camel integration routes, CXF web service endpoints, and ActiveMQ message queues within the ServiceMix ESB container.

**Human URL:** [https://servicemix.apache.org/](https://servicemix.apache.org/)

#### Tags:

 - Enterprise Integration, ESB, REST, Apache, Open Source

#### Properties

- [Documentation](https://servicemix.apache.org/)
- [OpenAPI](openapi/apache-servicemix-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/servicemix)
- [Documentation](https://servicemix.apache.org/)
- [SpectralRules](rules/apache-servicemix-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-servicemix-vocabulary.yaml)
- [NaftikoCapability](capabilities/servicemix-workflow.yaml)
- [JSON-LD](json-ld/apache-servicemix-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| OSGi Container | Apache Karaf-based OSGi container for modular deployment |
| Apache Camel Routes | Rich integration routing with 300+ Camel components |
| Apache CXF | SOAP and REST web service hosting with CXF |
| ActiveMQ Messaging | Built-in JMS messaging with Apache ActiveMQ |
| Hot Deployment | Dynamic deployment of bundles and routes without restart |
| Enterprise Patterns | Support for EIP patterns including routing, transformation, and mediation |

## Use Cases

| Name | Description |
|------|-------------|
| Legacy System Integration | Connect legacy SOAP services with modern REST APIs |
| Message Routing | Route JMS messages between queues and topics |
| Service Orchestration | Orchestrate multiple services into composite workflows |
| Protocol Mediation | Transform between HTTP, JMS, JDBC, and file protocols |

## Integrations

| Name | Description |
|------|-------------|
| Apache Camel | Core integration framework providing routing and mediation |
| Apache CXF | SOAP and REST web service framework |
| Apache ActiveMQ | JMS message broker for asynchronous messaging |
| Apache Karaf | OSGi container and runtime |
| Spring Framework | Spring integration for bean management and transactions |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache ServiceMix REST API](openapi/apache-servicemix-rest-api.yaml)

### JSON Schema

- [Bundle](json-schema/apache-servicemix-bundle-schema.json)
- [Route](json-schema/apache-servicemix-route-schema.json)
- [Queue](json-schema/apache-servicemix-queue-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache ServiceMix JSON Structures](json-structure/)

### JSON-LD

- [Apache ServiceMix Context](json-ld/apache-servicemix-context.jsonld)

### Examples

- [Apache ServiceMix Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Integration Workflow](capabilities/servicemix-workflow.yaml) | Apache ServiceMix | 8 | Integration Developer, Platform Engineer |

## Vocabulary

- [Apache ServiceMix Vocabulary](vocabulary/apache-servicemix-vocabulary.yaml) — Unified taxonomy mapping ESB integration resources, actions, workflows, and personas

## Rules

- [Apache ServiceMix Spectral Rules](rules/apache-servicemix-spectral-rules.yml) — Rules enforcing Apache ServiceMix API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
