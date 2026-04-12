# AFARE Scoring System Requirements
## Affiliate Footprint & Readiness Evaluation

**Version:** 1.0
**Date:** 2026-04-11
**Owner:** Mac Ant (macant1099)
**Scoring Range:** 0-100 (5 dimensions x 20 points each)

---

## Overview

AFARE measures a brand's affiliate marketing footprint, program quality, partner ecosystem health, technical infrastructure, and readiness for LiveChannel integration. Each of the 5 dimensions contains 5 criteria scored 0-4, yielding a maximum of 20 points per dimension and 100 points overall.

### Scoring Bands

| Band | Range | Description |
|------|-------|-------------|
| Dormant | 0-24 | No meaningful affiliate presence; no program or severely underdeveloped |
| Emerging | 25-44 | Basic program exists but limited reach, weak terms, or poor infrastructure |
| Developing | 45-64 | Functional affiliate program with moderate network presence and standard terms |
| Established | 65-79 | Strong program with competitive terms, diverse partners, and solid tech stack |
| Leading | 80-100 | Best-in-class affiliate operation with broad network coverage, premium partners, and full LiveChannel readiness |

---

## Dimension 1: Program Presence (0-20)

Measures the breadth and discoverability of a brand's affiliate programs across major networks, niche platforms, and direct/private channels.

### 1.1 Major Network Coverage (CJ, ShareASale, Impact, Awin, Rakuten)

| Score | Definition |
|-------|------------|
| 0 | No presence on any of the 5 major affiliate networks |
| 1 | Present on 1 major network only |
| 2 | Present on 2 major networks |
| 3 | Present on 3-4 major networks with active program listings |
| 4 | Present on 4-5 major networks with active, well-maintained program listings and competitive terms on each |

### 1.2 Niche/Vertical Network Coverage

| Score | Definition |
|-------|------------|
| 0 | No presence on any niche or vertical-specific affiliate network |
| 1 | Present on 1 niche network (e.g., AvantLink, FlexOffers, Webgains, Indoleads, Commission Factory) but listing is minimal or inactive |
| 2 | Active presence on 1-2 niche/vertical networks relevant to the brand's category |
| 3 | Active presence on 3+ niche networks with category-appropriate positioning and updated program terms |
| 4 | Strategic coverage across 4+ niche/vertical networks with tailored terms per platform and demonstrated publisher recruitment on each |

### 1.3 Private/Direct Programs (In-House or via Refersion, GoAffPro, etc.)

| Score | Definition |
|-------|------------|
| 0 | No private or direct affiliate program; relies entirely on marketplace networks or has no program at all |
| 1 | Basic referral program exists (e.g., "refer a friend" with flat discount) but no structured affiliate tracking |
| 2 | Direct affiliate program exists via a third-party SaaS tool (Refersion, GoAffPro, FirstPromoter) with basic tracking and commission structure |
| 3 | In-house or managed direct program with dedicated affiliate portal, application process, custom commission tiers, and reporting dashboard |
| 4 | Sophisticated direct program with dedicated affiliate manager, custom onboarding, exclusive offers for direct partners, and integration with the brand's CRM/ERP for attribution |

### 1.4 LiveChannel/Membership Network Presence

| Score | Definition |
|-------|------------|
| 0 | No presence on any membership, subscription, or LiveChannel-style affiliate network |
| 1 | Brand has been discussed or listed on emerging membership/LiveChannel platforms but has no active program enrollment |
| 2 | Enrolled in 1 membership or LiveChannel-compatible network with basic program listing |
| 3 | Active on 2+ membership/LiveChannel networks with exclusive offers or membership-specific commission structures |
| 4 | Strategic LiveChannel presence with dedicated membership tiers, exclusive SKUs or bundles for channel partners, and real-time inventory/offer feeds |

### 1.5 Program Discoverability

| Score | Definition |
|-------|------------|
| 0 | No affiliate program page on the brand's website; program not discoverable via search engines |
| 1 | Affiliate program exists but is not linked from the main site; only discoverable via network directories or third-party affiliate program databases |
| 2 | Affiliate program page exists on the brand site (e.g., /affiliate or footer link) but contains minimal information (just a signup link) |
| 3 | Dedicated affiliate landing page with program details (commission rates, cookie duration, benefits), linked from site footer or partnership page, and indexed by search engines |
| 4 | Prominent affiliate program page with detailed terms, testimonials, earnings calculator, FAQ, and clear CTA; appears in top 3 search results for "[brand] affiliate program"; multiple entry points (footer, partnerships page, content creator hub) |

---

## Dimension 2: Commission & Terms (0-20)

Measures the competitiveness and attractiveness of a brand's affiliate commission structure and partnership terms. Thresholds are calibrated against category benchmarks from `category-benchmarks.json`.

### 2.1 Commission Rate Competitiveness (vs Category Benchmark)

| Score | Definition |
|-------|------------|
| 0 | No affiliate program or 0% commission offered |
| 1 | Commission rate is below the category low benchmark (bottom quartile). Consumer electronics: <2%; Bicycles DTC: <3% |
| 2 | Commission rate falls between the category low and median. Consumer electronics: 2-4.9%; Bicycles DTC: 3-4.9% |
| 3 | Commission rate is at or above the category median. Consumer electronics: 5-11.9%; Bicycles DTC: 5-11.9% |
| 4 | Commission rate is at or above the category high (top quartile) or offers volume-based escalators that reach top quartile. Consumer electronics: 12%+; Bicycles DTC: 12%+ |

### 2.2 Cookie Duration

| Score | Definition |
|-------|------------|
| 0 | No cookie tracking or session-only attribution (click must convert in same session) |
| 1 | Cookie duration of 1-7 days |
| 2 | Cookie duration of 8-20 days |
| 3 | Cookie duration of 21-45 days (at or above industry standard of 30 days) |
| 4 | Cookie duration of 46+ days, lifetime attribution, or multi-touch attribution model that credits the affiliate beyond last-click |

### 2.3 Payment Terms & Reliability

| Score | Definition |
|-------|------------|
| 0 | No clear payment terms published; reports of unpaid commissions or program instability |
| 1 | Payment terms exist but are unfavorable: high minimum payout threshold (>$100), infrequent payment schedule (quarterly+), or limited payment methods (check only) |
| 2 | Standard payment terms: monthly payouts, reasonable minimum ($25-$50), 2+ payment methods (PayPal, ACH), validation within 60 days |
| 3 | Favorable terms: net-30 to net-45 payment cycle, low minimum payout ($10-$25), 3+ payment methods including direct deposit, validation within 45 days |
| 4 | Best-in-class: net-30 or faster payment cycle, $0-$10 minimum payout, 4+ payment methods (PayPal, ACH, wire, check), commission validation within 30 days, transparent reversal policy, and documented on-time payment track record |

### 2.4 Tiered/Performance Incentives

| Score | Definition |
|-------|------------|
| 0 | Flat commission rate only; no performance incentives, bonuses, or tiered structures |
| 1 | Occasional promotional rate increases (e.g., holiday bumps) but no permanent tiered structure |
| 2 | Basic tiered structure: 2 tiers with modest commission uplift for hitting volume targets (e.g., base 5%, tier 2 at 7% for $5K+/month) |
| 3 | Multi-tier structure with 3+ levels, clear volume/performance thresholds, and meaningful commission increases (2x+ from base to top tier); may include bonus payments for new affiliate activation |
| 4 | Sophisticated incentive program: multiple commission tiers, performance bonuses, SPIFFs, contest/leaderboard programs, exclusive product access for top performers, and dedicated account management for high-volume affiliates |

### 2.5 Product-Level Commission Strategy

| Score | Definition |
|-------|------------|
| 0 | No product-level differentiation; single flat rate across all SKUs (or no program) |
| 1 | Minimal differentiation: 1-2 product categories with slightly different rates (e.g., accessories at base rate, premium products at base +1%) |
| 2 | Moderate differentiation: 3+ product categories with distinct commission rates reflecting margin differences; communicated to affiliates |
| 3 | Strategic product-level commissions: higher rates on new launches, hero products, or high-margin categories; lower rates on commodity/low-margin items; rates aligned with marketing objectives |
| 4 | Dynamic product-level strategy: commission rates vary by product, season, inventory level, and strategic priority; affiliates receive real-time rate cards; new product launch bonuses; clearance/overstock incentive rates; all documented and communicated proactively |

---

## Dimension 3: Partner Ecosystem (0-20)

Measures the health, diversity, and quality of a brand's affiliate partner base.

### 3.1 Active Affiliate Count

| Score | Definition |
|-------|------------|
| 0 | No active affiliates or program not accepting partners |
| 1 | 1-25 active affiliates generating clicks or sales in the trailing 90 days |
| 2 | 26-100 active affiliates with measurable activity |
| 3 | 101-500 active affiliates across multiple networks |
| 4 | 500+ active affiliates with evidence of ongoing recruitment and activation efforts |

### 3.2 Partner Type Diversity

| Score | Definition |
|-------|------------|
| 0 | No identifiable affiliate partners |
| 1 | Partners from only 1 type (e.g., coupon/deal sites only) |
| 2 | Partners from 2-3 types (e.g., coupon sites + a few content bloggers) |
| 3 | Partners from 4-5 types across: content/review sites, coupon/deal, comparison shopping, social media influencers, loyalty/cashback, and email publishers |
| 4 | Full-spectrum diversity across 6+ partner types including: content/review, coupon/deal, comparison, influencer/creator, loyalty/cashback, email, sub-affiliate networks, AI/agent affiliates, and technology partners |

### 3.3 Top Partner Quality

| Score | Definition |
|-------|------------|
| 0 | No identifiable top partners; no evidence of premium publisher relationships |
| 1 | Top partners are low-authority coupon/deal aggregators with limited editorial credibility |
| 2 | Some mid-tier content sites or niche bloggers among top partners; domain authority 20-40 |
| 3 | Multiple high-quality partners including recognized editorial publications (DA 40-70), established review sites, or category-leading content creators |
| 4 | Premium publisher relationships including tier-1 editorial (Wirecutter, CNET, Tom's Guide, PCMag; DA 70+), major comparison engines, and top-10 influencers in category; evidence of featured placements and dedicated reviews |

### 3.4 Content Creator Engagement

| Score | Definition |
|-------|------------|
| 0 | No content creator engagement; no influencer or creator program |
| 1 | Sporadic creator engagement; occasional product seeding but no structured program |
| 2 | Basic content creator program exists (e.g., application form, standard commission); 5-20 active creators |
| 3 | Structured creator program with dedicated landing page, tiered benefits, product seeding, and 20-100 active creators producing regular content |
| 4 | Best-in-class creator program: dedicated "SuperCharger" or ambassador tier, content grants, exclusive product access, co-created content, creator events, 100+ active creators, and measurable GMV attribution from creator-driven traffic |

### 3.5 AI Agent Affiliate Presence

| Score | Definition |
|-------|------------|
| 0 | No AI agent affiliates; no evidence of agent-compatible affiliate structures |
| 1 | Brand products appear in AI shopping results (ChatGPT, Perplexity, Google AI) but via third-party affiliates (e.g., Amazon Associates), not through direct brand affiliate links |
| 2 | Brand affiliate links are indexed and surfaced by at least 1 AI agent or shopping assistant; basic API or feed available for automated partners |
| 3 | Active partnerships with 2+ AI-powered shopping tools, comparison engines, or agent platforms; product data feeds optimized for agent consumption; affiliate-tracked links compatible with agent workflows |
| 4 | Dedicated AI agent affiliate tier with specialized commission structures, real-time API access, agent-optimized product feeds, and documented agent integration playbook; measurable revenue from agent-driven affiliate conversions |

---

## Dimension 4: Tracking & Attribution (0-20)

Measures the technical sophistication of a brand's affiliate tracking, reporting, creative support, and data infrastructure.

### 4.1 Tracking Technology

| Score | Definition |
|-------|------------|
| 0 | No affiliate tracking in place; manual or honor-system attribution only |
| 1 | Basic tracking via network-provided pixel or redirect links; cookie-only tracking with no fallback; susceptible to ad-blocker breakage |
| 2 | Standard network tracking (Impact, CJ, ShareASale, etc.) with cookie + server-side validation; basic fraud detection |
| 3 | Advanced tracking: server-to-server postback tracking, first-party cookie support, cross-device tracking, and ad-blocker resilient methods; multi-touch attribution awareness |
| 4 | Enterprise-grade tracking: server-side tracking with real-time validation, probabilistic + deterministic cross-device matching, SKU-level attribution, integration with the brand's CDP/analytics stack, and custom attribution modeling |

### 4.2 Real-Time Reporting

| Score | Definition |
|-------|------------|
| 0 | No affiliate reporting available to partners |
| 1 | Basic reporting: clicks and sales data available with 24-48 hour delay; manual CSV exports only |
| 2 | Standard network dashboard with daily reporting updates; breakdown by click, impression, sale, and commission; basic filtering and date range selection |
| 3 | Near real-time reporting (<4 hour delay) with advanced breakdowns: product-level, geo, device, traffic source; customizable dashboard and automated email reports |
| 4 | Real-time reporting dashboard with sub-hour data freshness; API access for programmatic report pulling; custom KPI dashboards; predictive analytics; A/B test reporting; EPC/conversion trend analysis tools |

### 4.3 Deep Linking Support

| Score | Definition |
|-------|------------|
| 0 | No deep linking capability; affiliates can only link to the brand's homepage |
| 1 | Deep linking technically possible but requires manual URL construction; no tooling or documentation provided |
| 2 | Network-provided deep link generator available (e.g., Impact deep link tool); can link to any product page; basic documentation |
| 3 | One-click deep link generation via browser extension or dashboard tool; vanity/custom URL support; automatic link encoding for existing content; documented deep link parameters |
| 4 | Full deep linking suite: browser extension, API-based link generation, automatic content link encoding, dynamic product-specific landing pages, deep link validation tool, and mobile app deep linking (universal links / app links) |

### 4.4 Creative Asset Library

| Score | Definition |
|-------|------------|
| 0 | No creative assets provided to affiliates |
| 1 | Basic text links and 1-2 generic banner ads; outdated or poorly designed assets |
| 2 | Standard creative library: 5-10 banner sizes, text links, seasonal promotions; updated quarterly |
| 3 | Comprehensive library: 15+ banner sizes/formats, product-specific banners, video assets, email templates, social media content; updated monthly; brand guidelines provided |
| 4 | Dynamic creative suite: auto-updating product banners with real-time pricing/availability, customizable widgets, product carousel embeds, co-branded landing page builder, A/B tested creative variants, and API-fed creative generation |

### 4.5 API/Feed Access

| Score | Definition |
|-------|------------|
| 0 | No product feed or API access for affiliates |
| 1 | Basic product feed available (CSV/XML) but updated infrequently (weekly+) with limited product attributes |
| 2 | Standard product data feed via network (Impact, CJ, etc.) with daily updates; includes core attributes (name, price, image, URL, category) |
| 3 | Rich product feed with daily+ updates, 20+ attributes per product (specs, reviews, stock status, shipping info), available in multiple formats (CSV, XML, JSON); basic API access for programmatic data retrieval |
| 4 | Full API suite: RESTful product API with real-time inventory/pricing, webhook notifications for price changes and stock events, promotional calendar API, commission rate API, and developer documentation with sandbox environment |

---

## Dimension 5: LiveChannel Readiness (0-20)

Measures a brand's readiness for integration with LiveChannel's membership-based affiliate commerce model, including platform compatibility, connector support, and scalability.

### 5.1 Shopify Platform Presence

| Score | Definition |
|-------|------------|
| 0 | Not on Shopify; uses a proprietary or non-standard ecommerce platform with no Shopify migration path |
| 1 | On Shopify Basic or a legacy Shopify plan; limited storefront customization; single region/store |
| 2 | On Shopify standard plan with functional DTC storefront; basic theme customization; standard checkout |
| 3 | On Shopify Plus with multi-region storefronts, custom checkout (Checkout Extensibility), headless/hydrogen storefront, or advanced Shopify APIs in use |
| 4 | Shopify Plus enterprise deployment: 10+ global storefronts, headless architecture (Hydrogen/Oxygen or custom), Shopify Functions for custom logic, full Storefront API utilization, and demonstrated ability to onboard new sales channels rapidly |

### 5.2 CX Connector Compatibility

| Score | Definition |
|-------|------------|
| 0 | No CX (Customer Experience) connectors; no integration with CRM, helpdesk, or customer engagement platforms relevant to affiliate channel |
| 1 | Basic CX stack (e.g., Zendesk or Shopify Inbox for support) but no affiliate-relevant connector or integration |
| 2 | CX stack includes 1-2 connectors relevant to affiliate commerce: e.g., Klaviyo for email, Mailchimp, or a loyalty platform; basic Shopify app integrations |
| 3 | Integrated CX stack with 3+ connectors: CRM (Salesforce, HubSpot), email (Klaviyo), loyalty (Smile.io, Yotpo), analytics (GA4/Amplitude), and at least one affiliate-attribution-aware touchpoint |
| 4 | Full CX connector ecosystem: CRM + email + loyalty + analytics + CDP + affiliate tracking all integrated; customer journey from affiliate click through post-purchase is tracked end-to-end; affiliate partners receive CX-informed audience segments or co-op marketing capabilities |

### 5.3 Membership Model Fit

| Score | Definition |
|-------|------------|
| 0 | No subscription, membership, or recurring revenue model; purely transactional one-time purchases |
| 1 | Brand offers occasional bundles or multi-packs but no recurring or membership model; no affiliate-compatible subscription offering |
| 2 | Basic subscription or membership element exists (e.g., email newsletter VIP access, loyalty points program) but not integrated with affiliate channel |
| 3 | Active subscription/membership offering (e.g., product subscription, VIP club with tangible benefits, recurring delivery) with affiliate-trackable signup or conversion events |
| 4 | Sophisticated membership commerce: tiered membership with exclusive pricing/products, affiliate-trackable recurring commissions on membership signups and renewals, member-only offers that affiliates can promote, and demonstrated LTV uplift from membership customers |

### 5.4 Exclusive Offer Capability

| Score | Definition |
|-------|------------|
| 0 | No capability to create exclusive offers for affiliate partners; no coupon or promotional infrastructure |
| 1 | Basic coupon functionality exists (Shopify discount codes) but no process for creating affiliate-exclusive offers |
| 2 | Can create unique coupon codes per affiliate or affiliate group; basic exclusive offer capability but manual process |
| 3 | Structured exclusive offer program: dedicated affiliate promo codes, vanity URLs, exclusive bundles or early access for affiliate audiences; managed through affiliate network or in-house tool |
| 4 | Dynamic exclusive offer platform: automated unique-per-affiliate discount codes, real-time offer management, exclusive product bundles, time-limited flash offers via affiliate API, and partner-specific landing pages with exclusive pricing |

### 5.5 Multi-Network Scalability

| Score | Definition |
|-------|------------|
| 0 | No affiliate program or present on only 1 network with no demonstrated ability to expand |
| 1 | Present on 1 network; program structure is tightly coupled to that network's tooling; expansion would require significant rework |
| 2 | Present on 1-2 networks with standardized program terms that could be replicated on additional networks; basic multi-network awareness |
| 3 | Active on 3+ networks/platforms with consistent brand messaging, coordinated commission structures, and cross-network deduplication in place; proven ability to launch on new networks |
| 4 | Operates a hub-and-spoke affiliate model: centralized program management (via Impact, Partnerize, or in-house) distributing to 5+ networks and direct partnerships simultaneously; automated cross-network deduplication, unified reporting, and rapid onboarding to new networks/channels including LiveChannel |

---

## Scoring Methodology

### Calculation

```
Dimension Score = Sum of 5 criteria scores (0-4 each) = 0-20
Total AFARE Score = Sum of 5 dimension scores = 0-100
```

### Evidence Requirements

Every score must include:
1. **Specific evidence** supporting the assigned score (URL, screenshot, data point, or direct observation)
2. **Date of observation** to enable score change tracking
3. **Confidence level** (High/Medium/Low) based on evidence quality

### Score Change Tracking

Score changes are tracked via structured YAML blocks appended to each vendor scorecard (same pattern as ACES scoring system). Each change records: previous score, new score, delta, evidence, and affected dimensions.

### Category Benchmark Integration

Dimension 2 (Commission & Terms) criteria are calibrated against category-specific benchmarks stored in `benchmarks/category-benchmarks.json`. When scoring a vendor, the evaluator must:
1. Identify the vendor's primary category
2. Reference the corresponding benchmark thresholds
3. Score relative to those thresholds, not absolute values

---

## Relationship to Other Scoring Systems

| System | Owner | Focus |
|--------|-------|-------|
| ACES | Mac Bee | Agent Commerce Enablement (protocol, payment, discoverability, security, data) |
| Signal | Mac Bee | Brand Intelligence (AI discovery, search, sentiment, competitive, content) |
| AFARE | Mac Ant | Affiliate Footprint & Readiness (program presence, commission, partners, tracking, LiveChannel) |

AFARE complements ACES and Signal by evaluating a brand's affiliate-specific infrastructure, which is the commercial backbone for LiveChannel's membership-based agent commerce model. A brand with high ACES but low AFARE scores has good agentic commerce readiness but poor affiliate monetization infrastructure.
