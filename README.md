# Newscatcher (newscatcher)

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
