# ZDNet (zdnet)
ZDNet is a business technology news website owned by Ziff Davis, covering enterprise IT, cybersecurity, cloud computing, hardware, software, and innovation for IT professionals and tech-savvy business leaders. ZDNet provides news, analysis, product reviews, and how-to guides. No public developer API is available; content is accessible via RSS feeds.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Enterprise IT, Media, Technology News

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-03

## APIs

### ZDNet RSS Feed
RSS feeds providing the latest news, analysis, and reviews from ZDNet covering enterprise IT, security, cloud, hardware, software, artificial intelligence, and business technology for IT professionals.

**Human URL:** [https://www.zdnet.com/news/rss.xml](https://www.zdnet.com/news/rss.xml)

#### Tags:

 - Artificial Intelligence, Cloud, Enterprise IT, News Feed, RSS, Security, Technology News

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/openapi/zdnet-rss.yml)
- [RSS](https://www.zdnet.com/news/rss.xml)
- [RSS](https://www.zdnet.com/topic/security/rss.xml)
- [RSS](https://www.zdnet.com/topic/cloud/rss.xml)
- [RSS](https://www.zdnet.com/topic/artificial-intelligence/rss.xml)
- [RSS](https://www.zdnet.com/topic/developer/rss.xml)
- [RSS](https://www.zdnet.com/topic/innovation/rss.xml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-schema/)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-structure/)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-ld/zdnet-rss-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/examples/)

## Common Properties

- [Website](https://www.zdnet.com/)
- [About](https://www.zdnet.com/about-zdnet/)
- [RSS](https://www.zdnet.com/news/rss.xml)
- [RSS](https://www.zdnet.com/topic/security/rss.xml)
- [RSS](https://www.zdnet.com/topic/cloud/rss.xml)
- [RSS](https://www.zdnet.com/topic/artificial-intelligence/rss.xml)
- [RSS](https://www.zdnet.com/topic/developer/rss.xml)
- [Newsletter](https://www.zdnet.com/newsletters/)
- [Team](https://www.zdnet.com/meet-the-team/)
- [Advertising](https://www.zdnet.com/advertise/)
- [EditorialGuidelines](https://www.zdnet.com/article/zdnet-editorial-guidelines/)
- [PrivacyPolicy](https://www.zdnet.com/privacy-policy/)
- [TermsOfService](https://www.zdnet.com/terms-of-use/)
- [X](https://x.com/ZDNet)
- [LinkedIn](https://www.linkedin.com/company/zdnet-com)
- [Facebook](https://www.facebook.com/ZDNet)
- [Podcast](https://podcasts.apple.com/us/podcast/zdnet-video/id271364310)
- [SpectralRules](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/rules/zdnet-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/vocabulary/zdnet-vocabulary.yml)
- [NaftikoCapability](https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/capabilities/zdnet-workflow.yaml)

## Features

| Name | Description |
|------|-------------|
| RSS News Feed | Latest enterprise IT news from ZDNet. |
| Topic-Specific Feeds | Filtered RSS feeds for security, cloud, AI, developer, and innovation topics. |
| RSS 2.0 Format | Standard XML RSS 2.0 format for syndication. |

## Use Cases

| Name | Description |
|------|-------------|
| News Aggregation | Aggregate ZDNet articles into a news app or dashboard. |
| Topic Monitoring | Monitor specific topic feeds (security, cloud, AI) for industry tracking. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [zdnet-rss.yml](openapi/zdnet-rss.yml)

### JSON Schema

- [rss-rss-feed-schema.json](json-schema/rss-rss-feed-schema.json)
- [rss-rss-item-schema.json](json-schema/rss-rss-item-schema.json)

### JSON Structure

- [rss-rss-feed-structure.json](json-structure/rss-rss-feed-structure.json)
- [rss-rss-item-structure.json](json-structure/rss-rss-item-structure.json)

### JSON-LD

- [zdnet-rss-context.jsonld](json-ld/zdnet-rss-context.jsonld)

### Examples

- [rss-rss-feed-example.json](examples/rss-rss-feed-example.json)
- [rss-rss-item-example.json](examples/rss-rss-item-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ZDNet RSS Feed API](capabilities/shared/rss.yaml) — 6 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [ZDNet Workflow](capabilities/zdnet-workflow.yaml) | 1 | 6 | Developer |

## Vocabulary

- [ZDNet Vocabulary](vocabulary/zdnet-vocabulary.yml) — Unified taxonomy mapping 2 resources, 1 actions, 1 workflows, and 1 personas

## Rules

- [zdnet-rules.yml](rules/zdnet-rules.yml) — 18 rules enforcing ZDNet API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
