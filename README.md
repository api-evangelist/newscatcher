# Newscatcher (newscatcher)

Newscatcher is a news search and aggregation API platform providing access to over 120,000 news sources worldwide with full-text search, NLP enrichment, entity extraction, sentiment analysis, automated clustering, and vector embeddings. The platform offers three core products: a News API for structured article retrieval, a Web Search (CatchAll) API for recall-first AI-grade web search, and a Local News API for hyper-local geographic news coverage. Newscatcher is backed by Y Combinator (S22) and holds ISO certifications and SOC2 Type II compliance, serving enterprise customers in financial services, AI platforms, government, defense, insurance, and media intelligence.

APIs.json: https://raw.githubusercontent.com/api-evangelist/newscatcher/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=newscatcher-api-evangelist&utm_content=repo

## Tags

News, Search, NLP, Sentiment Analysis, Entity Extraction, Clustering, Media Intelligence, Financial Intelligence, AI, Enterprise

## APIs

| Name | Description | Docs |
|------|-------------|------|
| News API | Structured access to 120,000+ news sources with NLP, entity recognition, sentiment, IPTC tagging, and embeddings | [Docs](https://www.newscatcherapi.com/docs/v3/api-reference/overview/introduction) |
| CatchAll Web Search API | Recall-first web search API for AI agents with credit-based pricing and monitor slots | [Docs](https://www.newscatcherapi.com/docs) |
| Local News API | Hyper-local geographic news coverage with NLP enrichment | [Docs](https://www.newscatcherapi.com/docs) |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/newscatcher-plans-pricing.yml](plans/newscatcher-plans-pricing.yml) |
| Rate Limits | [rate-limits/newscatcher-rate-limits.yml](rate-limits/newscatcher-rate-limits.yml) |
| FinOps | [finops/newscatcher-finops.yml](finops/newscatcher-finops.yml) |

**Web Search API** uses a self-service credit-based model: Individual ($0/mo), Starter ($50/mo, 6,000 credits), Scale ($500/mo, 60,000 credits), Enterprise (custom). Unused credits roll over. Lite mode costs 100 credits/search; Base mode costs 10 credits/valid record.

**News API** is an enterprise product with three plan tiers — NLP, IPTC Tags, and Embeddings — priced on request. Plans define monthly call quotas, concurrent call limits, and historical data depth. The `/subscription` endpoint reports real-time quota consumption.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.newscatcherapi.com |
| Documentation | https://www.newscatcherapi.com/docs |
| GitHub Org | https://github.com/Newscatcher |
| LinkedIn | https://www.linkedin.com/company/newscatcherapi |
| Blog | https://www.newscatcherapi.com/blog |
| Pricing | https://www.newscatcherapi.com/pricing |
| Status Page | https://status.newscatcherapi.com |
| X / Twitter | https://x.com/newscatcherapi |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
