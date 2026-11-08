# Awesome-API-Governance-Linting-Spectral

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag the data problem before you publish this.

## What the search results actually support

**Pricing (usable):**
- **42Crunch**: Individual plan **$9/month** (1,000 security tokens, 1 user, +$0.03 per extra token); Individual Pro **$20/month** (3,000 tokens) . Free version limited to **25 Audit and 25 Scan executions per month per repo, max 3 repos** . Paid enterprise syncs with platform for customizable Security Quality Gates and data dictionaries .
- **Redocly**: **Pro $10/seat/month** (1 project, 100 pages); **Enterprise $24/seat/month** (500 pages, SSO, RBAC, MCP servers); Enterprise+ custom . **Redocly CLI is MIT licensed** and free .
- **Postman API Governance**: **Enterprise plans only** . No standalone pricing surfaced.
- **Snyk**: Team **$25/dev/month** (5-developer floor, 10-developer cap); Ignite **$1,260/dev/year** up to 50 developers; Enterprise custom . Free tier has **weekly test frequency** .

**Open-source tools (usable):**
- **Spectral**: The most popular open-source API linter, MIT licensed. Swagger Studio's custom rules are **underpinned by Spectral** . YAML/JSON rulesets with core functions (truthy, pattern, casing, schema, etc.) and custom JavaScript functions .
- **Vacuum**: "World's fastest" OpenAPI/AsyncAPI/JSON Schema linter, **100% compatible with Spectral rulesets** . Benchmarks: **6.1MB Stripe spec linted in 0.85s (73% faster than v0.23)** . Supports OpenAPI 3.0/3.1/3.2, AsyncAPI, custom Go/JS functions, and has a dashboard and HTML report .
- **Optic**: OpenAPI linting, diffing, and testing. **Runs any existing Spectral ruleset** via `optic.yml`, with added "only new/changed" scoping and breaking-change detection . Used by Snyk for API governance .

**What is missing:**
- **No star counts** for Spectral, Vacuum, or Optic in the results.
- **No pricing** for SwaggerHub Governance (Swagger Studio) or Stoplight.
- **No revenue or valuation** for any vendor.
- **No confirmation** that "Stoplight Spectral" is a separate product—Spectral is an open-source project, and Stoplight is the original creator, but the search results describe Spectral as open source without a Stoplight-specific commercial wrapper beyond Swagger Studio's use .
- **No information** on Fern Linter or Speakeasy CLI's linting depth beyond "lint and validate OpenAPI specs"  and Fern's `check.rules` severity configuration for docs validation .

## What I recommend

**The open-source section is genuinely strong.** Spectral, Vacuum, and Optic are all real, active, and functionally overlapping but distinct:
- **Spectral** is the de facto standard rules engine .
- **Vacuum** is the performance-focused, Spectral-compatible alternative .
- **Optic** adds diffing and breaking-change detection on top of Spectral .

**The SaaS section has usable pricing for 42Crunch, Redocly, and Snyk, but not for Postman (Enterprise-only), SwaggerHub, or Stoplight.** If you include those, mark pricing as "quote-only" rather than fabricating figures.

**Drop "Stoplight Spectral" as a SaaS product.** Spectral is the open-source project; Stoplight is its originator. List Spectral in the open-source section, and Swagger Studio (formerly SwaggerHub) in the SaaS section as the commercial wrapper that uses it .

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate star counts, SwaggerHub/Stoplight pricing, or a commercial "Stoplight Spectral" product that the results do not support.
