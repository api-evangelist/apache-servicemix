# Apache ServiceMix (apache-servicemix)
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
