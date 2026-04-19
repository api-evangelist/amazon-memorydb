# Amazon MemoryDB (amazon-memorydb)
Amazon MemoryDB for Redis is a durable, in-memory database service that delivers ultra-fast performance. It is Redis-compatible and provides microsecond reads, low single-digit millisecond writes, and enterprise-grade security.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-memorydb/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon MemoryDB API
Amazon MemoryDB for Redis is a durable, in-memory database service that delivers ultra-fast performance. It is Redis-compatible and provides microsecond reads, low single-digit millisecond writes, and enterprise-grade security.

**Human URL:** [https://aws.amazon.com/memorydb/](https://aws.amazon.com/memorydb/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/memorydb/)
- [OpenAPI](openapi/amazon-memorydb-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/memorydb/getting-started/)
- [Pricing](https://aws.amazon.com/memorydb/pricing/)
- [FAQ](https://aws.amazon.com/memorydb/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/memorydb/)
- [Documentation](https://docs.aws.amazon.com/memorydb/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/memorydb/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Redis Compatibility | Fully compatible with Redis and Memcached data structures, APIs, and commands. |
| Durable In-Memory Storage | Multi-AZ transactional log ensures data durability without sacrificing performance. |
| Ultra-Fast Performance | Microsecond read and low single-digit millisecond write latency at scale. |
| Cluster Management | Create and manage MemoryDB clusters, shards, and replicas with ease. |
| Snapshot and Restore | Create point-in-time snapshots for backup and restore operations. |
| Access Control Lists | Fine-grained access control with user-based ACLs for security. |
| Multi-Region Clusters | Deploy clusters across multiple AWS regions for global low-latency access. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Session Management | Store session data with ultra-low latency for modern microservices applications. |
| Real-Time Leaderboards | Maintain sorted sets for gaming leaderboards and ranking systems. |
| Caching Layer | Use as a durable caching layer to reduce database load and improve response times. |
| Pub/Sub Messaging | Build real-time messaging and event streaming with Redis pub/sub patterns. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon VPC | Deploy MemoryDB clusters within a VPC for network isolation. |
| AWS KMS | Encrypt data at rest using AWS Key Management Service keys. |
| Amazon CloudWatch | Monitor cluster metrics including cache hits, memory usage, and connections. |
| AWS IAM | Control access using IAM policies and roles. |
| Amazon ElastiCache | Migrate from ElastiCache Redis to MemoryDB for durable storage. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon MemoryDB OpenAPI](openapi/amazon-memorydb-openapi-original.yml)

### JSON Schema

- 9 schema files in [json-schema/](json-schema/)

### JSON Structure

- 9 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon MemoryDB API Context](json-ld/amazon-memorydb-memorydb-api-context.jsonld)

### Examples

- 9 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon MemoryDB](capabilities/shared/memorydb.yaml) — 34 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon MemoryDB Workflow](capabilities/amazon-memorydb-media-workflow.yaml) | Amazon MemoryDB | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon MemoryDB Vocabulary](vocabulary/amazon-memorydb-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon MemoryDB Spectral Rules](rules/amazon-memorydb-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon MemoryDB API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
