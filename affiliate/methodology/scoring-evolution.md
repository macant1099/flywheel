# Scoring Evolution Log
_Weekly methodology review results. Each entry documents whether scoring dimensions, criteria, or sources need to change._

---

## Review #1 — 2026-04-13 (Week 1)

**Reviewer:** Mac Ant (automated weekly cron)
**Vendors Scored:** 2 (Anker 64, Priority Bicycles 46)
**Score Changes This Week:** 1 (Priority Bicycles 44→46, +2, Partner Ecosystem upgrade)
**Weeks of Data:** <1 (system created 2026-04-11)

---

### Dimension Evaluations

**Dimension 1: Program Presence (0-20)**
- Sub-criteria relevance: All 5 criteria performed well. Major Network Coverage (1.1) and Niche Network Coverage (1.2) discriminated clearly between Anker (2, 3) and Priority (0, 2). LiveChannel/Membership Presence (1.4) scored low for both vendors (1, 0) — expected at this stage of the market but worth watching for floor effect.
- New signals to consider: Instagram Reels native affiliate tagging (March 2026 rollout) could warrant a social commerce presence sub-criterion under Program Presence in the future. Not enough evidence yet.
- Source issues: None. Network presence is verifiable via direct observation.
- Discrimination: Good. 12 vs. 9 (3-point spread).

**Dimension 2: Commission & Terms (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- ⚠️ **Scoring inconsistency found:** Priority Bicycles Cookie Duration (2.2) is scored as 2, but the rubric defines Score 3 as "21-45 days" and Priority has a 21-day cookie. Per the rubric letter, this should be a 3. The scorecard narrative correctly notes it's "below category median" but the raw criterion measures absolute duration, not category-relative duration. **Action:** Fix Priority's 2.2 from 2→3 in next scoring pass, OR amend rubric 2.2 to explicitly make thresholds category-relative. Recommending the fix (score to 3) since the rubric is clear.
- New signals: TikTok Shop hybrid compensation (guaranteed floor + commission) is emerging as a new standard for creator recruitment. Current criterion 2.4 (Tiered/Performance Incentives) doesn't capture hybrid models well. Monitor for 2+ more weeks before adjusting.
- Source issues: Payment Terms (2.3) is hard to verify externally — relies on affiliate review sites and network documentation which may be outdated. Confidence is Medium for both vendors.
- Discrimination: Good. 14 vs. 9 (5-point spread).

**Dimension 3: Partner Ecosystem (0-20)**
- Sub-criteria relevance: All 5 criteria working. Active Affiliate Count (3.1) is the weakest — exact counts are almost never disclosed publicly, requiring estimation. Both vendors are scored on estimates.
- New signals: The Rad Power Bikes bankruptcy/acquisition (Dec 2025 → Mar 2026) surfaced a new signal type: competitor program instability creates recruitment windows. This is captured via competitive analysis but not as a formal scoring criterion. No action needed — it's context, not a scoreable attribute.
- Source issues: Active Affiliate Count (3.1) confidence is Low for both vendors. Consider adding a standard estimation methodology (network footprint × average activation rate) to reduce subjectivity.
- AI Agent Affiliate Presence (3.5): Both vendors score 1/4. This criterion is forward-looking and may produce a floor effect across all vendors until AI agent affiliate programs become more common. Retain for now — it's strategically important for LiveChannel's thesis.
- Discrimination: Adequate after upgrade. 13 vs. 11 (2-point spread). Tightest dimension.

**Dimension 4: Tracking & Attribution (0-20)**
- Sub-criteria relevance: All 5 criteria working. Network platform capability (Impact vs. AvantLink) is the dominant score driver. This is by design — the tracking dimension should reflect actual infrastructure.
- New signals: Cookie deprecation is causing real attribution gaps (2026 briefing headline). Current criterion 4.1 (Tracking Technology) captures server-side tracking at score 3+, which correctly rewards brands with modern tracking. No rubric change needed.
- Source issues: Creative Asset Library (4.4) and API/Feed Access (4.5) are hard to assess without affiliate account access. Scores rely on program descriptions and third-party reviews. Confidence is Medium.
- Discrimination: Good. 13 vs. 9 (4-point spread).

**Dimension 5: LiveChannel Readiness (0-20)**
- Sub-criteria relevance: All 5 criteria working. Shopify Platform Presence (5.1) produced the widest single-criterion spread (4 vs. 2) — strong discriminator.
- Membership Model Fit (5.3): Both vendors score 1/4. This is a genuine gap in the market, not a rubric problem. Most DTC brands haven't built membership commerce models yet. Retain criterion.
- Source issues: CX Connector Compatibility (5.2) requires inference from tech stack analysis (BuiltWith, Shopify app directory, job postings). Methodology is sound but labor-intensive.
- Discrimination: Good. 12 vs. 8 (4-point spread).

---

### Benchmark Evaluation

**category-benchmarks.json status:** Accurate for current vendor set.
- `consumer_electronics`: Commission rates (2-12%, median 5%) confirmed by Anker (8%), Belkin (4%), UGREEN (8-15%) research. No update needed.
- `bicycles_dtc`: Commission rates (3-12%, median 5%) confirmed by Priority (5%), Aventon (4%), Trek (4-8%). Cookie duration benchmarks (15-90d, median 30d) confirmed. No update needed.
- `portable_power` and `fitness_equipment`: Not yet tested against scored vendors. Will validate when vendors in those categories are scored.
- **New benchmark data this week:** Levanta's Perch+ acquisition suggests Amazon-native affiliate commission benchmarks (15-25%) should be tracked separately. Consider adding an `amazon_native` benchmark category in future. Not urgent — no vendors currently scored on Levanta.

---

### Rubric Changes

**Proposed (deferred pending 3-week evidence threshold):** None warranting immediate rubric change.

**Scoring fix required (not a rubric change):**
- Priority Bicycles criterion 2.2 (Cookie Duration): Score should be 3 (21 days falls in 21-45 day band), not 2. To be corrected in next scoring pass. Net effect: Priority total 46→47.

---

### Source Recommendations

| Source | Status | Recommendation |
|--------|--------|----------------|
| Network program pages (Impact, AvantLink) | Reliable | Continue as primary |
| Affiliate review aggregators (AuthorityHacker, GetLasso) | Useful for discovery, sometimes outdated | Cross-reference with direct sources |
| BuiltWith / Shopify app directory | Reliable for tech stack | Continue |
| Tier-1 editorial (Wirecutter, PCMag, etc.) | Reliable for partner quality | Continue |
| AI shopping tools (ChatGPT, Perplexity) | Useful for 3.5 scoring | Formalize test queries per vendor |

---

### Gap Findings

| Gap | Recurring Weeks | Status | Notes |
|-----|----------------|--------|-------|
| Active Affiliate Count (3.1) estimation methodology undefined | 1 | OPEN | Need standard formula: network count × est. activation rate |
| Payment Terms (2.3) hard to verify externally | 1 | OPEN | Consider requiring affiliate account signup for validation |
| Creative assets (4.4) and API/feeds (4.5) assessable only from outside | 1 | OPEN | Same as above — affiliate account access would improve confidence |
| AI Agent Affiliate (3.5) floor effect — both vendors at 1/4 | 1 | MONITORING | Expected at market stage; retain criterion for strategic value |
| Membership Model (5.3) floor effect — both vendors at 1/4 | 1 | MONITORING | Market-wide gap, not rubric issue |

---

### Notes

- This is the inaugural AFARE methodology review. The system was created on 2026-04-11 with 2 vendors scored. Sample size is too small (n=2) to draw meaningful conclusions about rubric discrimination or calibration. Target: 5+ vendors scored before making any rubric changes.
- The scoring inconsistency on Priority's cookie duration (2.2) suggests adding a "rubric compliance check" step to the scoring workflow — after scoring, verify each criterion score against the rubric thresholds mechanically.
- Three major industry signals this week (Instagram Reels affiliate, Levanta/Perch+, FTC AI endorsement enforcement) are relevant to future rubric evolution but don't warrant immediate changes. Logged for tracking.
- Next vendor categories to score (portable_power, fitness_equipment) will stress-test the remaining benchmark categories. Prioritize scoring a vendor in each within the next 2 weeks.
- **No rubric changes made. Evidence threshold (3+ weeks) not met for any proposed change.**

---

## Review #2 — 2026-04-19 (Week 2)

**Reviewer:** Mac Ant (automated weekly cron)
**Vendors Scored:** 2 (Anker 65, Priority Bicycles 46)
**Score Changes This Week:** 1 (Anker 64→65, +1, Partner Ecosystem 3.3 upgrade on 2026-04-14)
**Weeks of Data:** ~1.5 (system created 2026-04-11)
**No +/-5 score movements this week.**

---

### Key Industry Signals This Week

1. **Amazon Associates policy overhaul (Apr 14)** — HIGH: 180-day ship deadline, paid traffic disqualified, onsite commissions narrowed to exact ASIN. Structural reduction in Amazon affiliate earnings.
2. **FTC AI disclosure requirements escalating** — HIGH: Program contracts now expected to include AI disclosure clauses (Affiverse analysis Apr 15). Joint liability extends to program operators.
3. **Target ends cash commission creator program** — HIGH: Replaced with gamified gift card rewards. Signals some retailers retreating from cash commissions.
4. **TikTok Shop hybrid compensation standard** — MEDIUM: Flat fee ($100-500/video) + 15-20% commission emerging as the creator deal standard (week 2 of tracking).
5. **Influencers = 53% of all affiliate partnerships** — MEDIUM: Affilae 2026 platform data confirms creator/influencer majority.
6. **Google March 2026 update crushed affiliate SEO sites** — MEDIUM: AEO (Answer Engine Optimization) emerging as alternative channel.
7. **Cookie deprecation operational reality** — MEDIUM (recurring): Server-side tracking now standard. California privacy law lawsuit (Ace Hardware) reinforces urgency.
8. **FlexOffers T&C update (Apr 16)** — MEDIUM: Traffic source pre-approval now required. Compliance tightening across networks.

### Competitor Baselines Established

- **UGREEN:** Impact + ShareASale, 8-15% tiered, 30d cookie. Validates consumer_electronics benchmark.
- **Belkin:** Impact, 0.8-4%, 30d cookie. At/below category low — confirms benchmark floor.
- **RAVPower:** In-house only, 8-15%, 30d cookie. Amazon-banned since 2021. High nominal rate but severely limited distribution.

---

### Dimension Evaluations

**Dimension 1: Program Presence (0-20)**
- Sub-criteria relevance: All 5 criteria still relevant and performing well.
- New signals: Amazon Associates policy tightening doesn't change Program Presence scoring but reduces the value of Amazon-mediated program presence. No rubric change needed.
- Source issues: None. Network presence remains verifiable via direct observation.
- Discrimination: 12 vs. 9 (3-point spread) — unchanged, adequate.
- **Verdict: No changes.**

**Dimension 2: Commission & Terms (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- ⚠️ **Pending fix from Review #1:** Priority 2.2 Cookie Duration still scored as 2; rubric says 21 days = score 3. Correction still needed in next scoring pass.
- **Monitoring (week 2/3):** TikTok Shop hybrid compensation (flat fee + commission) is now corroborated by 3 independent sources across 2 weeks. Current criterion 2.4 (Tiered/Performance Incentives) captures bonuses and tiered structures but doesn't explicitly address hybrid guaranteed-floor models. If this signal persists to week 3, propose adding "hybrid/guaranteed floor compensation" as an explicit qualifier at score 3-4 in criterion 2.4.
- Amazon Associates April 14 changes reduce effective commission yield for Amazon-mediated affiliates (ASIN-only attribution, paid traffic exclusion). This may depress real-world commission benchmarks over time. No benchmark change yet — need to observe actual rate adjustments.
- Target's move away from cash commissions is an outlier so far (1 retailer). Monitor.
- Source issues: Payment Terms (2.3) confidence remains Medium. Recurring gap (week 2).
- Discrimination: 14 vs. 9 (5-point spread) — good.
- **Verdict: No rubric changes. Priority 2.2 fix still pending.**

**Dimension 3: Partner Ecosystem (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- Affilae data (influencers = 53% of partnerships) validates 3.4 (Content Creator Engagement) as a critical scoring dimension. No change needed.
- Google March 2026 update crushing affiliate SEO sites is a structural threat to traditional content affiliate partners (3.1, 3.2, 3.3). AEO emergence strengthens the strategic importance of 3.5 (AI Agent Affiliate Presence). No rubric change yet — observing.
- 3.1 (Active Affiliate Count) estimation methodology still undefined (week 2). **Action: Draft estimation formula by Review #3.** Proposed: `estimated_active = network_count × avg_activation_rate × program_age_factor`.
- AI Agent Affiliate (3.5) floor effect continues — both vendors at 1/4. Expected given market stage. Retain.
- Discrimination: 14 vs. 11 (3-point spread) — adequate but tightest dimension.
- **Verdict: No changes. Estimation methodology draft due next week.**

**Dimension 4: Tracking & Attribution (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- Cookie deprecation confirmed as operational reality (3 independent signals this week). Current 4.1 rubric already rewards server-side tracking at score 3+. Correctly calibrated.
- California privacy law enforcement (Ace Hardware lawsuit, $42K avg fines) + FlexOffers T&C tightening signal a new compliance dimension. Current rubric doesn't explicitly score compliance infrastructure. **Monitoring:** If compliance enforcement continues to surface as a tracking differentiator (privacy-compliant tracking vs. non-compliant), consider adding a compliance qualifier to 4.1 at score 3-4 level. Not yet warranted.
- Source issues: Creative assets (4.4) and API/feeds (4.5) confidence remains Medium. Recurring gap (week 2).
- Discrimination: 13 vs. 9 (4-point spread) — good.
- **Verdict: No changes.**

**Dimension 5: LiveChannel Readiness (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- No new signals directly affecting LiveChannel scoring this week.
- Membership Model (5.3) floor effect continues — both vendors at 1/4. Market-wide gap, not rubric issue.
- Discrimination: 12 vs. 8 (4-point spread) — good.
- **Verdict: No changes.**

---

### Benchmark Evaluation

**category-benchmarks.json status:** Accurate for current vendor set.
- `consumer_electronics`: UGREEN baseline (8-15%, 30d) and Belkin audit (0.8-4%, 30d) both validate the current low/median/high range (2%/5%/12%). No update needed.
- `bicycles_dtc`: No new competitor data this week. Benchmarks hold.
- `portable_power` and `fitness_equipment`: Still untested against scored vendors. Target: score a vendor in each within the next week.
- **Amazon Associates policy impact:** The April 14 policy changes (ASIN-only commissions, paid traffic exclusion) may structurally depress effective Amazon affiliate commission rates over time. No benchmark adjustment yet — need to observe real-world rate changes over 2-4 weeks. Flagged for Review #3.
- **New benchmark data this week:** None that invalidates current ranges.

---

### Rubric Changes

**None.** Evidence threshold (3+ weeks of data) not met for any proposed change.

**Deferred proposals (tracking toward 3-week threshold):**

| Proposal | Signal | Weeks Tracked | Threshold | Status |
|----------|--------|--------------|-----------|--------|
| Add hybrid compensation qualifier to 2.4 | TikTok Shop flat+commission model | 2 | 3 | MONITORING — 3 corroborating sources. Decision at Review #3. |
| Add compliance qualifier to 4.1 | Cookie deprecation + privacy enforcement | 2 | 3 | MONITORING — Observing whether compliance becomes a tracking differentiator. |
| Instagram Reels affiliate sub-criterion | Social commerce native tagging | 2 | 3 | MONITORING — Insufficient vendor-level evidence. |

**Scoring fix still pending (from Review #1):**
- Priority Bicycles criterion 2.2 (Cookie Duration): Score should be 3 (21 days falls in 21-45 day band), not 2. Net effect when applied: Priority total 46→47.

---

### Source Recommendations

| Source | Status | Recommendation |
|--------|--------|----------------|
| Network program pages (Impact, AvantLink) | Reliable | Continue as primary |
| Affiliate review aggregators (AuthorityHacker, GetLasso) | Useful for discovery, sometimes outdated | Cross-reference with direct sources |
| BuiltWith / Shopify app directory | Reliable for tech stack | Continue |
| Tier-1 editorial (Wirecutter, PCMag, etc.) | Reliable for partner quality | Continue |
| AI shopping tools (ChatGPT, Perplexity) | Useful for 3.5 scoring | Formalize test queries per vendor |
| Affiverse Media | NEW — Strong for regulatory/compliance signals | Add to regular monitoring rotation |
| AffiliateCMS forums | NEW — Early signal on network policy changes (FlexOffers, Amazon) | Add to regular monitoring rotation |
| Short Form Nation | NEW — TikTok Shop commission benchmarks | Add to social commerce monitoring |

---

### Gap Findings

| Gap | Recurring Weeks | Status | Notes |
|-----|----------------|--------|-------|
| Active Affiliate Count (3.1) estimation methodology undefined | 2 | OPEN — Draft due Review #3 | Proposed formula: network_count × avg_activation_rate × program_age_factor |
| Payment Terms (2.3) hard to verify externally | 2 | OPEN | Consider affiliate account signup for validation |
| Creative assets (4.4) and API/feeds (4.5) assessable only from outside | 2 | OPEN | Affiliate account access would improve confidence |
| AI Agent Affiliate (3.5) floor effect — both vendors at 1/4 | 2 | MONITORING | AEO emergence strengthens long-term relevance of criterion |
| Membership Model (5.3) floor effect — both vendors at 1/4 | 2 | MONITORING | Market-wide gap, not rubric issue |
| Priority 2.2 cookie score fix pending | 2 | OPEN — Carry forward | Flagged in Review #1, still not applied to scorecard |
| Amazon Associates effective commission impact on benchmarks | 1 | NEW — MONITORING | Apr 14 policy changes may depress real-world rates |

---

### Notes

- **Week 2 of AFARE methodology.** Sample size still small (n=2 vendors scored). Rubric stability is encouraging — no dimension has shown scoring failures or obvious miscalibration. All 5 dimensions produce adequate discrimination (3-5 point spreads).
- **Three HIGH-impact industry signals this week** (Amazon Associates overhaul, FTC AI disclosure, Target creator program change) all affect the affiliate ecosystem structurally but don't yet warrant rubric changes. They're environment shifts, not measurement methodology issues.
- **TikTok hybrid compensation is the strongest candidate for a rubric amendment** — 3 corroborating sources across 2 weeks. If evidence continues to week 3, will propose adding hybrid compensation language to criterion 2.4 at the score 3-4 level. Conservative approach: this is an additive qualifier, not a restructuring.
- **Competitor baselines (UGREEN, Belkin, RAVPower) are valuable benchmark validators** — all three confirm current category-benchmarks.json ranges without requiring adjustment. UGREEN's 8-15% tiered structure is the most aggressive competitive offer against Anker.
- **AEO (Answer Engine Optimization) is a structural emerging signal** for Dimension 3 (Partner Ecosystem). As AI-powered answer engines replace Google for product discovery, the affiliate publisher landscape will shift. Criterion 3.5 (AI Agent Affiliate Presence) is already positioned for this. No change needed but importance is rising.
- **Priority scoring targets:** Score vendors in `portable_power` and `fitness_equipment` categories to stress-test remaining benchmark categories. This was flagged in Review #1 and should be prioritized this coming week.
- **No rubric changes made. Evidence threshold (3+ weeks) not met for any proposed change.**

---

## Review #3 — 2026-04-26 (Week 3)

**Reviewer:** Mac Ant (automated weekly cron)
**Vendors Scored:** 2 (Anker 65, Priority Bicycles 47)
**Score Changes This Week:** 1 (Priority Bicycles 46→47, +1, Partner Ecosystem 3.3 upgrade on 2026-04-25)
**Weeks of Data:** ~2.5 (system created 2026-04-11)
**No +/-5 score movements this week.**

---

### Key Industry Signals This Week

1. **AI retail traffic +393% YoY, converts 42% better than humans (Adobe Q1 2026)** — HIGH: Revenue per visit 37% higher. The AI-agent-as-affiliate channel has shifted from experimental to top-performing in 12 months. Repeated across every briefing this week — the signal is saturating.
2. **Meta launches native affiliate tools on Instagram and Facebook** — HIGH: Shoppable Reels (30 product tags), affiliate banners, Partnership Ads Hub. Amazon, eBay, Shopee, Temu, Mercado Libre as launch partners. Adoption slow outside beauty/wellness.
3. **Instagram "Shop the Look" AI auto-tagging controversy** — MEDIUM: AI visual recognition auto-tagging products in creator content without explicit consent. Attribution ambiguity and creator rights issues.
4. **Anthropic Project Deal: AI agents negotiate real purchases** — HIGH: 186 deals, $4K+ in actual goods. "Agent quality gap" — more advanced models achieve objectively better outcomes. Proves agent-to-agent commerce is real, not theoretical.
5. **Performance-based influencer compensation hits 53% adoption** — MEDIUM: Doubled in 2 years (Influencer Marketing Factory). Convergence of influencer and affiliate accelerating.
6. **Partnerize launches "Lighthouse Program" for AI-driven influence compensation** — MEDIUM: ML-optimized commission calculation. Manual affiliate management being outpaced.
7. **Ulta Beauty live with Google agentic commerce via Gemini** — MEDIUM: Google's Universal Commerce Protocol (UCP) in production. Another major retailer betting on agent commerce.
8. **Cookie deprecation operational reality (week 3)** — MEDIUM (recurring): Server-side tracking now standard. No new enforcement data but signal stable.
9. **FTC disclosure fines at $53,088/instance, enforcement up 40%** — HIGH (recurring): AI content rules now active. Joint liability extends to program operators.
10. **Levanta acquires Perch+** — MEDIUM: Network consolidation continues. All-in-one aggregation platforms gaining ground.

### Competitor Baselines This Week

- **Belkin:** Competitor audit (2026-04-24) detected "rate compression" — Belkin at 0.8-4% (category low). Validates consumer_electronics benchmark floor. No benchmark change needed.
- No new competitor scoring data for bicycles_dtc, portable_power, or fitness_equipment.

---

### Dimension Evaluations

**Dimension 1: Program Presence (0-20)**
- Sub-criteria relevance: All 5 criteria remain relevant and performing well.
- New signals: Meta's Instagram/Facebook native affiliate tools (week 3 of tracking) strengthen the case for eventual social commerce platform presence consideration. However, 1.4 (LiveChannel/Membership Network Presence) is distinct from social-native affiliate. Instagram affiliate is closer to 1.2 (Niche/Vertical Network Coverage) or a new dimension entirely. No change warranted — Meta tools are a platform feature, not a network listing a vendor would "enroll" in.
- Source issues: None. Network presence verifiable via direct observation.
- Discrimination: 12 vs. 9 (3-point spread) — unchanged, adequate.
- **Verdict: No changes.**

**Dimension 2: Commission & Terms (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- ⚠️ **Priority 2.2 Cookie Duration fix status:** The scoring fix (2→3) was NOT applied to the scorecard during this period. However, Priority's score moved 46→47 via a 3.3 Partner Quality upgrade on 2026-04-25. The 2.2 fix remains pending. **Action: Apply in next scoring pass. Expected effect: Priority 47→48.**
- **TikTok hybrid compensation (week 3/3 threshold reached):** 3+ corroborating sources across 3 weeks. Performance-based compensation at 53% adoption (Influencer Marketing Factory). Portland Leather Goods $1M TikTok blitz used contest/bonus mechanics. However, the hybrid model (flat fee + commission) is primarily a *TikTok Shop creator deal structure*, not a program-level commission structure that AFARE measures. Current criterion 2.4 already captures "bonus payments for new affiliate activation" at score 3 and "SPIFFs, contest/leaderboard programs" at score 4. The hybrid model fits within existing rubric language. **Decision: No rubric change. Existing 2.4 language at scores 3-4 already accommodates hybrid compensation structures. Close tracking.**
- Amazon Associates effective commission impact: 2 weeks since policy changes. No observed benchmark-level shifts yet. Continue monitoring.
- Discrimination: 14 vs. 9 (5-point spread) — good.
- **Verdict: No rubric changes. Priority 2.2 fix still pending (week 3). TikTok hybrid tracking CLOSED — existing rubric sufficient.**

**Dimension 3: Partner Ecosystem (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- AI Agent Affiliate (3.5): Adobe's 393% AI traffic surge + 42% better conversion + Anthropic Project Deal + Google UCP in production with Ulta all strengthen the strategic importance of this criterion. Both vendors still at 1/4. Floor effect persists but is market-stage appropriate, not a rubric flaw. Importance is accelerating — this criterion may become the most differentiated in AFARE within 6-12 months as early-mover vendors build agent affiliate tiers.
- 3.1 Active Affiliate Count estimation methodology: **Due this review.** Proposed formula: `estimated_active = Σ(network_visibility_score) × category_activation_rate × program_age_factor`. Deferred again — insufficient data points (n=2) to validate any formula. Need 5+ vendors scored first. **Rescheduled to Review #5 or when n≥5 vendors scored, whichever comes first.**
- Instagram "Shop the Look" AI auto-tagging raises attribution questions for 3.2 (Partner Type Diversity) — if platforms auto-create affiliate relationships without explicit enrollment, how do we count those partners? Not a scoring issue yet. Monitoring.
- Discrimination: 14 vs. 12 (2-point spread) — tightest dimension. Compressed further from last week (was 14 vs. 11). Both vendors upgrading partner quality (3.3) narrows the spread. Not a rubric problem — it reflects genuine similarity in editorial partner quality for two well-positioned DTC brands.
- **Verdict: No changes. 3.1 estimation formula deferred to Review #5 or n≥5.**

**Dimension 4: Tracking & Attribution (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- Cookie deprecation (week 3/3 threshold): Server-side tracking is confirmed operational standard. Current 4.1 rubric scores server-side tracking at 3+ and cookie-only at 1-2. This correctly discriminates. **No rubric change needed — existing 4.1 already captures the cookieless transition.**
- Compliance qualifier for 4.1 (week 3/3 threshold): FTC fines at $53K/instance + enforcement up 40% + AI content disclosure rules. However, compliance is a *legal/program management* concern, not a *tracking technology* measurement. Adding compliance to Dimension 4 would conflate technical infrastructure with program governance. **Decision: Do not add compliance qualifier to 4.1. If compliance becomes a scoring dimension, it belongs as a new Dimension 6 or as a cross-cutting modifier — not within Tracking & Attribution. Close tracking for Dimension 4; open new monitoring item for potential Dimension 6.**
- Partnerize "Lighthouse Program" (AI-driven commission optimization) is a network-level feature, not a vendor-scored attribute. No rubric impact.
- Source issues: Creative assets (4.4) and API/feeds (4.5) confidence remains Medium. Recurring gap (week 3).
- Discrimination: 13 vs. 9 (4-point spread) — good.
- **Verdict: No changes. Compliance qualifier CLOSED for Dim 4; new monitoring item opened for potential standalone compliance dimension.**

**Dimension 5: LiveChannel Readiness (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- Google UCP (Universal Commerce Protocol) in production with Ulta + Shopify integration: This strengthens the strategic relevance of 5.1 (Shopify Platform Presence) and 5.5 (Multi-Network Scalability). Vendors on Shopify Plus may gain UCP compatibility as a built-in advantage. No rubric change — UCP readiness is captured indirectly by existing criteria.
- Membership Model (5.3) floor effect continues — both vendors at 1/4. Week 3. Market-wide gap, not rubric issue.
- Discrimination: 12 vs. 8 (4-point spread) — good.
- **Verdict: No changes.**

---

### Benchmark Evaluation

**category-benchmarks.json status:** Accurate. No updates required.
- `consumer_electronics`: Belkin rate compression audit (2026-04-24) confirms 0.8-4% range at category low. UGREEN 8-15% at category high. Anker 8% above median. Benchmarks validated by 3 competitor data points. Stable.
- `bicycles_dtc`: No new competitor data this week. Priority at 5% (median). Benchmarks hold.
- `portable_power` and `fitness_equipment`: Still untested against scored vendors. **Week 3 of flagging — no vendors scored in these categories yet.** Deprioritized until pipeline produces a vendor in either category.
- **Amazon Associates effective commission impact:** Week 2 of monitoring. No observable benchmark shifts yet. Amazon's ASIN-only attribution + paid traffic exclusion may take 1-2 quarters to show up in aggregate data. Continue monitoring; next check at Review #5.
- **New benchmark data this week:** Portland Leather Goods TikTok Shop data ($1M in 20 days, 500 creators) suggests a `social_commerce` benchmark category may be needed eventually. Not actionable for current vendor set.

---

### Rubric Changes

**None.** All three proposals that reached the 3-week threshold were evaluated and determined to be already covered by existing rubric language or inappropriate for the proposed dimension.

**Deferred proposals resolved this review:**

| Proposal | Signal | Weeks Tracked | Decision | Rationale |
|----------|--------|--------------|----------|-----------|
| Add hybrid compensation qualifier to 2.4 | TikTok Shop flat+commission model | 3 ✓ | **CLOSED — No change** | Existing 2.4 language at scores 3-4 ("bonus payments," "SPIFFs," "contest/leaderboard programs") already accommodates hybrid compensation. |
| Add compliance qualifier to 4.1 | Cookie deprecation + privacy enforcement | 3 ✓ | **CLOSED for Dim 4 — New monitoring item opened** | Compliance is a legal/program governance concern, not a tracking technology measurement. If it becomes a scoring dimension, it belongs as a potential Dimension 6, not within Dim 4. |
| Instagram Reels affiliate sub-criterion | Social commerce native tagging | 3 ✓ | **CLOSED — No change** | Meta's affiliate tools are platform features, not network enrollments a vendor would be scored on. Social commerce is a partner type (captured in Dim 3) not a program presence attribute (Dim 1). |

**New monitoring items:**

| Proposal | Signal | Weeks Tracked | Threshold | Status |
|----------|--------|--------------|-----------|--------|
| Potential Dimension 6: Compliance & Governance | FTC enforcement, AI disclosure, privacy law | 1 (new) | 5 | MONITORING — Only add a 6th dimension with very strong evidence (structural change, not cyclical). Higher threshold than sub-criteria amendments. |
| AI Agent Affiliate (3.5) scoring bands | Adobe 393% AI traffic, Anthropic Project Deal, UCP | 1 (new) | Watch | MONITORING — As vendors begin building agent affiliate tiers, the 3.5 rubric may need band recalibration to discriminate between first-movers. Not urgent while both vendors at 1/4. |

**Scoring fix still pending (from Review #1, week 3):**
- Priority Bicycles criterion 2.2 (Cookie Duration): Score should be 3 (21 days falls in 21-45 day band), not 2. **Apply in next scoring pass. Expected effect: Priority 47→48.**

---

### Source Recommendations

| Source | Status | Recommendation |
|--------|--------|----------------|
| Network program pages (Impact, AvantLink) | Reliable | Continue as primary |
| Affiliate review aggregators (AuthorityHacker, GetLasso) | Useful for discovery, sometimes outdated | Cross-reference with direct sources |
| BuiltWith / Shopify app directory | Reliable for tech stack | Continue |
| Tier-1 editorial (Wirecutter, PCMag, etc.) | Reliable for partner quality | Continue |
| AI shopping tools (ChatGPT, Perplexity) | Useful for 3.5 scoring | Formalize test queries per vendor |
| Affiverse Media | Reliable for regulatory/compliance signals | Continue in rotation |
| AffiliateCMS forums | Useful for early network policy signals | Continue in rotation |
| Short Form Nation | Useful for TikTok Shop commission benchmarks | Continue in rotation |
| Adobe Analytics (Q1 2026 data) | NEW — Authoritative for AI traffic benchmarks | Reference for 3.5 scoring context |
| Influencer Marketing Factory reports | NEW — Creator economy compensation benchmarks | Reference for 3.4 / Dim 2 context |
| Google UCP documentation | NEW — Emerging standard for agent commerce | Monitor for 5.5 scoring implications |

---

### Gap Findings

| Gap | Recurring Weeks | Action Status | Notes |
|-----|----------------|---------------|-------|
| Active Affiliate Count (3.1) estimation methodology undefined | 3 | DEFERRED → Review #5 or n≥5 vendors | Insufficient data points (n=2) to validate any formula |
| Payment Terms (2.3) hard to verify externally | 3 | OPEN | Consider affiliate account signup for validation. Low urgency — both vendors scored at Medium confidence. |
| Creative assets (4.4) and API/feeds (4.5) assessable only from outside | 3 | OPEN | Affiliate account access would improve confidence. Same mitigation as 2.3. |
| AI Agent Affiliate (3.5) floor effect — both vendors at 1/4 | 3 | MONITORING | Market-stage appropriate. Importance accelerating (Adobe 393%, Anthropic Project Deal, UCP). Watch for first vendor to build agent tier. |
| Membership Model (5.3) floor effect — both vendors at 1/4 | 3 | MONITORING | Market-wide gap, not rubric issue |
| Priority 2.2 cookie score fix pending | 3 | **OVERDUE — Apply in next scoring pass** | Flagged Review #1, still not applied. Priority 47→48 when fixed. |
| Amazon Associates effective commission impact on benchmarks | 2 | MONITORING | Apr 14 policy changes. No observable shifts yet. Next check: Review #5. |
| Vendor sample size (n=2) limits rubric validation | 3 | OPEN | Target n≥5 before making structural rubric changes. portable_power and fitness_equipment categories still unscored. |
| Potential Dimension 6 (Compliance & Governance) | 1 (new) | MONITORING | High evidence threshold (5 weeks). FTC $53K fines, AI disclosure, privacy. |

---

### Notes

- **Week 3 of AFARE methodology.** All three deferred proposals reached the 3-week evidence threshold and were evaluated. All three were resolved without rubric changes — existing language either already covered the signals or the proposed placement was inappropriate. This validates the conservative approach: the rubric is proving more resilient than expected.
- **Sample size remains the primary constraint.** With n=2 vendors scored, discrimination analysis is directional at best. The 2-point spread on Dimension 3 (Partner Ecosystem) isn't alarming but can't be distinguished from coincidence. Priority: expand to n≥5 vendors before next structural review.
- **AI agent commerce signals are saturating.** Adobe's 393% traffic number appeared in every briefing this week. Anthropic's Project Deal adds behavioral proof (agents negotiating real transactions). Google's UCP is in production with Ulta. The convergence of these signals validates that criterion 3.5 (AI Agent Affiliate Presence) is correctly positioned as forward-looking — and its importance will grow faster than any other criterion in AFARE.
- **Priority 2.2 scoring fix is now 3 weeks overdue.** This is a simple rubric compliance correction (21 days is in the 21-45 day band = score 3, not 2). Must be applied in the next scoring pass. No excuses at week 3.
- **Meta's social commerce affiliate play is significant** but doesn't require AFARE rubric changes. Social-native affiliate (Instagram Reels, Facebook affiliate banners) is a distribution channel for existing affiliate programs, not a new program structure that vendors build. It will show up in scoring through 3.2 (Partner Type Diversity) and 3.4 (Content Creator Engagement) when vendors' affiliates use these tools.
- **Compliance as a potential Dimension 6:** FTC enforcement at $53K/instance, AI disclosure rules, and privacy law are real. But AFARE is a *footprint and readiness* measurement, not a *governance* assessment. Adding Dimension 6 would change what AFARE measures. Set a high threshold (5 weeks) and require structural evidence that compliance is a differentiator in affiliate program quality, not just an industry cost.
- **No rubric changes made. No benchmark changes made. Methodology stable through week 3.**

---

## Review #4 — 2026-05-03 (Week 4)

**Reviewer:** Mac Ant (automated weekly cron)
**Vendors Scored:** 2 (Anker 65, Priority Bicycles 47)
**Score Changes This Week:** 0
**Weeks of Data:** ~3.5 (system created 2026-04-11)
**No +/-5 score movements this week.**

---

### Key Industry Signals This Week

1. **Rakuten × Impact.com strategic alliance (Apr 29)** — CRITICAL: Rakuten exits affiliate platform technology entirely; all merchants/publishers migrate to Impact.com's infrastructure. Rakuten becomes a "Titanium Partner" publisher. The biggest structural event in affiliate infrastructure in a decade. Directly affects Dimension 1 scoring methodology (see below).
2. **Experian launches "Agent Trust" with Visa and Cloudflare (May 2)** — HIGH: Real-time trust tokens binding verified human identity to AI agents. "Know Your Agent" protocol. The identity layer agentic commerce was missing — makes AI agents trackable and commissionable.
3. **Visa launches "Intelligent Commerce" for AI agents (May 3)** — HIGH: Payment rails for agentic purchases now live from a major financial infrastructure company.
4. **A2A (Agent-to-Agent) protocol reaches 150+ production deployments (May 3)** — HIGH: Linux Foundation's April 2026 release confirmed. Live on Azure AI Foundry, Amazon Bedrock AgentCore, Salesforce. Agent-to-merchant negotiation is production-scale.
5. **GRIN launches free affiliate infrastructure (May 1)** — MEDIUM: Zero platform fees, monetized through AI agent "Gia." Creator-economy pricing model eating traditional affiliate SaaS.
6. **EMARKETER: affiliate drives $241B in US ecommerce, $13.81B in spend (2026)** — MEDIUM: Channel scale confirmed. Measurement gap remains the industry's primary problem.
7. **Shopify AI-driven traffic up 8x YoY, orders up 15x (May 1)** — HIGH: Merchants discoverable in ChatGPT, Copilot, Google AI Mode, Gemini. Agentic commerce has a native Shopify integration layer.
8. **Performance-based creator contracts at 53% adoption** — MEDIUM (recurring): Flat-fee influencer deals are now the minority model. Affiliate-style compensation is the new default.
9. **Meta Facebook Affiliate Partnerships expanding** — MEDIUM: eBay joined beta, Shopee live across 8 markets. Native affiliate layer inside Meta's social graph.
10. **Fintel Connect/Cornerstone report: banks missing affiliate opportunity** — LOW: 43% of FI marketers don't incorporate affiliate until after budgets set. Niche vertical signal.

### Vendor Audit Findings This Week

- **Anker (Apr 30):** Discovered **Rakuten Advertising / LinkShare as active US network** (mid=43469, signup live on program page). Previously only Impact was confirmed as a major US network. Rakuten is now listed as primary US network with Impact as secondary.
- **Anker (May 2):** Discovered **Webgains UK program** (ID 289655) separate from Nordics. UK commission refined to 7-12% range (previously logged as 7% flat). Daily datafeed confirmed for UK program.
- **Anker (May 2):** Network footprint now confirmed: Rakuten (US primary), Impact (US secondary), Webgains Nordics (310162), Webgains UK (289655), CueLinks (India), Indoleads (SEA). Total: 2 major networks + 4 niche/regional networks.
- **Priority Bicycles (Apr 27–May 3):** 11 consecutive audit cycles with zero changes. Program completely stable. AvantLink + Yazing, 5% flat, 21-day cookie.

---

### Dimension Evaluations

**Dimension 1: Program Presence (0-20)**
- Sub-criteria relevance: All 5 criteria remain relevant.
- ⚠️ **CRITICAL METHODOLOGY QUESTION — Rakuten × Impact.com merger impact on 1.1 scoring:** The Rakuten/Impact alliance will migrate Rakuten merchants to Impact's infrastructure. For vendors like Anker that are active on *both* Rakuten and Impact, the post-merger network count becomes ambiguous. Are they on 2 major networks (Rakuten + Impact) or effectively 1 (combined platform)? **Decision: Score based on current observable state.** As of today, Rakuten and Impact operate as separate enrollments with separate program IDs, dashboards, and publisher pools. Score accordingly. When migration completes (expected mid-summer 2026), re-evaluate whether the combined entity should count as 1 or 2 for 1.1 purposes. **New monitoring item opened.**
- Anker 1.1 status: With Rakuten now confirmed active alongside Impact, Anker has 2 major networks = score 2 per rubric. No score change (was already scored 2, which was generous given only Impact was confirmed previously — the original scoring may have anticipated Rakuten based on partial evidence).
- Source issues: None. Network presence remains verifiable via direct observation.
- Discrimination: 12 vs. 9 (3-point spread) — unchanged, adequate.
- **Verdict: No changes. Rakuten/Impact merger methodology question opened for monitoring.**

**Dimension 2: Commission & Terms (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- ⚠️ **Priority 2.2 Cookie Duration fix — WEEK 4 OVERDUE.** Score should be 3 (21 days = 21-45 day band), not 2. This fix has been flagged every review since #1. **Escalation: This is now a mandatory correction. Must be applied before Review #5.** Expected effect: Priority 47→48.
- Anker UK commission refined to 7-12% range (was 7% flat). This doesn't change the 2.1 score (8% US rate is the primary benchmark) but enriches the evidence for 2.5 (Product-Level Commission Strategy).
- Shopify 2026 commission benchmarks (hybrid 15-25% new / 5-10% returning) are useful context for scoring but don't affect current vendor evaluations — neither vendor uses hybrid new/returning structures.
- Source issues: Payment Terms (2.3) confidence remains Medium (week 4). Recurring.
- Discrimination: 14 vs. 9 (5-point spread) — good.
- **Verdict: No rubric changes. Priority 2.2 fix MANDATORY before Review #5.**

**Dimension 3: Partner Ecosystem (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- AI Agent Affiliate (3.5): This was the biggest signal week for agentic commerce since AFARE's creation. Experian Agent Trust + Visa Intelligent Commerce + A2A at 150+ deployments = the identity, payment, and communication layers for AI-agent-as-affiliate are now all in production or launching. Floor effect persists (both vendors at 1/4) but the urgency for vendors to build agent affiliate tiers has dramatically accelerated. When the first scored vendor builds a dedicated agent tier, 3.5 will become a strong discriminator.
- Meta Facebook Affiliate expanding: eBay joining confirms this is a real partner channel. Will affect 3.2 (Partner Type Diversity) when vendors' affiliates adopt Meta's native tools. No rubric change needed.
- 3.1 Active Affiliate Count estimation: Deferred to Review #5 or n≥5 vendors (from Review #3). Still at n=2. No action.
- Discrimination: 14 vs. 12 (2-point spread) — tightest dimension. Both vendors have strong editorial coverage (3.3 at 4/4 for both), compressing the spread. Not a rubric problem — genuine similarity.
- **Verdict: No changes.**

**Dimension 4: Tracking & Attribution (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- Rakuten/Impact merger has tracking implications: Anker currently on both platforms. Post-merger, tracking will consolidate onto Impact's infrastructure. This strengthens Anker's tracking baseline (Impact's enterprise features) but doesn't change the current score.
- Anker UK Webgains program confirms daily datafeed updates — enriches 4.5 (API/Feed Access) evidence slightly but doesn't change the score (still network-provided, not a dedicated brand API).
- Experian Agent Trust creates a new attribution pathway for AI agent traffic. Current 4.1 rubric doesn't explicitly cover agent-identity-based attribution. Not a scoring concern yet — no vendors are using Agent Trust. **Monitoring: If Agent Trust adoption becomes a tracking differentiator within 6 months, consider adding agent-attribution language to 4.1 at score 4 level.**
- Source issues: Creative assets (4.4) and API/feeds (4.5) confidence remains Medium (week 4). Recurring.
- Discrimination: 13 vs. 9 (4-point spread) — good.
- **Verdict: No changes. Agent Trust attribution monitoring item opened.**

**Dimension 5: LiveChannel Readiness (0-20)**
- Sub-criteria relevance: All 5 criteria working.
- Shopify AI-driven traffic up 8x / orders up 15x: Validates 5.1 (Shopify Platform Presence) as a critical differentiator. Shopify merchants are now discoverable across AI surfaces natively. Anker (Shopify Plus, 4/4) benefits directly. Priority (Shopify standard, 2/4) benefits partially. No rubric change — existing scoring already rewards Shopify Plus over standard.
- GRIN's free affiliate infrastructure could affect 5.5 (Multi-Network Scalability) by lowering barriers to launching on new platforms. Not a scoring issue yet.
- Membership Model (5.3) floor effect continues — both vendors at 1/4 (week 4). Market-wide gap.
- Discrimination: 12 vs. 8 (4-point spread) — good.
- **Verdict: No changes.**

---

### Benchmark Evaluation

**category-benchmarks.json status:** Accurate. No updates required.
- `consumer_electronics`: Anker network discovery (Rakuten + Impact both active) and UK rate refinement (7-12%) don't change benchmark ranges. Current low/median/high (2%/5%/12%) validated. No update.
- `bicycles_dtc`: Priority stable at 5% / 21d. No new competitor data. Benchmarks hold.
- `portable_power` and `fitness_equipment`: Still untested against scored vendors (week 4 of flagging). Deprioritized until pipeline produces a vendor.
- **Rakuten/Impact alliance impact on benchmarks:** The consolidation may reduce effective network competition, potentially affecting commission rate benchmarks over time (less competition = less pressure to offer competitive rates). Speculative — no observable impact yet. Monitor through 2026.
- **New benchmark data this week:** Shopify's published hybrid commission benchmarks (15-25% new / 5-10% returning) are useful industry context but represent a different model than AFARE's category-based benchmarks. No change to category-benchmarks.json.

---

### Rubric Changes

**None.** No evidence this week warrants rubric changes.

**New monitoring items:**

| Proposal | Signal | Weeks Tracked | Threshold | Status |
|----------|--------|--------------|-----------|--------|
| 1.1 methodology: Rakuten/Impact post-merger network counting | Rakuten × Impact alliance (Apr 29) | 1 (new) | Post-migration | MONITORING — Score on current observable state. Re-evaluate when migration completes (est. mid-summer 2026). |
| 4.1 language: Agent-identity-based attribution (Agent Trust) | Experian Agent Trust (May 2) | 1 (new) | 6 months | MONITORING — If Agent Trust adoption becomes a tracking differentiator, add language to 4.1 at score 4 level. |
| 3.5 scoring bands: Agent tier differentiation | Experian + Visa + A2A infrastructure week | 2 | Watch | MONITORING — Carry from Review #3. No vendors with agent tiers yet. |
| Potential Dimension 6: Compliance & Governance | FTC enforcement, AI disclosure, privacy law | 2 | 5 | MONITORING — Carry from Review #3. No new enforcement data this week. |

**Scoring fix still pending (from Review #1, WEEK 4 OVERDUE):**
- Priority Bicycles criterion 2.2 (Cookie Duration): Score should be 3 (21 days falls in 21-45 day band), not 2. **MANDATORY: Apply before Review #5. Expected effect: Priority 47→48.**

---

### Source Recommendations

| Source | Status | Recommendation |
|--------|--------|----------------|
| Network program pages (Impact, AvantLink, Rakuten) | Reliable | Continue as primary. Note: Rakuten dashboard may change during migration. |
| Affiliate review aggregators (AuthorityHacker, GetLasso) | Useful for discovery, sometimes outdated | Cross-reference with direct sources |
| BuiltWith / Shopify app directory | Reliable for tech stack | Continue |
| Tier-1 editorial (Wirecutter, PCMag, etc.) | Reliable for partner quality | Continue |
| AI shopping tools (ChatGPT, Perplexity) | Useful for 3.5 scoring | Formalize test queries per vendor |
| Affiverse Media | Reliable for regulatory/compliance signals | Continue in rotation |
| AffiliateCMS forums | Useful for early network policy signals | Continue in rotation |
| Short Form Nation | Useful for TikTok Shop commission benchmarks | Continue in rotation |
| Adobe Analytics (Q1 2026 data) | Authoritative for AI traffic benchmarks | Reference for 3.5 scoring context |
| Influencer Marketing Factory reports | Creator economy compensation benchmarks | Reference for 3.4 / Dim 2 context |
| Google UCP documentation | Emerging standard for agent commerce | Monitor for 5.5 scoring implications |
| Experian Agent Trust documentation | NEW — Identity infrastructure for agentic commerce | Monitor for 4.1 / 3.5 scoring implications |
| Visa Intelligent Commerce | NEW — Payment rails for AI agent transactions | Monitor for agentic commerce readiness |

---

### Gap Findings

| Gap | Recurring Weeks | Action Status | Notes |
|-----|----------------|---------------|-------|
| Active Affiliate Count (3.1) estimation methodology undefined | 4 | DEFERRED → Review #5 or n≥5 vendors | Insufficient data points (n=2) to validate any formula |
| Payment Terms (2.3) hard to verify externally | 4 | OPEN | Consider affiliate account signup for validation. Low urgency. |
| Creative assets (4.4) and API/feeds (4.5) assessable only from outside | 4 | OPEN | Affiliate account access would improve confidence. |
| AI Agent Affiliate (3.5) floor effect — both vendors at 1/4 | 4 | MONITORING | Infrastructure week (Agent Trust + Visa + A2A) accelerates timeline. Watch for first vendor to build agent tier. |
| Membership Model (5.3) floor effect — both vendors at 1/4 | 4 | MONITORING | Market-wide gap, not rubric issue |
| Priority 2.2 cookie score fix pending | **4 — OVERDUE** | **MANDATORY — Apply before Review #5** | Flagged Review #1. 21 days = score 3 per rubric. Priority 47→48 when fixed. |
| Amazon Associates effective commission impact on benchmarks | 3 | MONITORING | Apr 14 policy changes. No observable shifts. Next check: Review #5. |
| Vendor sample size (n=2) limits rubric validation | 4 | OPEN | Target n≥5 before structural rubric changes. |
| Potential Dimension 6 (Compliance & Governance) | 2 | MONITORING | High threshold (5 weeks). No new enforcement data this week. |
| Rakuten/Impact post-merger network counting methodology | 1 (new) | MONITORING | Score on current state until migration completes (est. mid-summer 2026). |

---

### Notes

- **Week 4 of AFARE methodology.** The rubric continues to prove stable — no dimension has required changes through 4 weekly reviews. All 5 dimensions produce adequate discrimination (2-5 point spreads). The 2-point Dimension 3 spread is the tightest but reflects genuine vendor similarity in editorial partner quality, not a rubric flaw.
- **The Rakuten × Impact.com alliance is the single largest structural event since AFARE was created.** It doesn't require immediate rubric changes but introduces a methodology question about network counting that will need resolution when the migration completes. For now, score on observable state: Anker has separate active enrollments on both platforms.
- **Agentic commerce infrastructure had its breakout week.** Experian Agent Trust (identity), Visa Intelligent Commerce (payments), and A2A at 150+ deployments (communication) all landed within days. Combined with Shopify's 8x AI traffic growth, the full stack for AI-agent-as-affiliate is assembling. Criterion 3.5 remains the most strategically important forward-looking criterion in AFARE. The floor effect (both vendors at 1/4) will break when the first vendor builds a dedicated agent affiliate tier — and the infrastructure that arrived this week makes that more likely in Q3/Q4 2026.
- **Priority 2.2 scoring fix is 4 weeks overdue.** This is a simple rubric compliance correction that has been flagged in every single review. Escalating to MANDATORY status. The fix must be applied to the scorecard before Review #5 runs. No further deferrals.
- **Sample size (n=2) remains the primary constraint** on rubric validation. No new vendor categories scored this week. The portable_power and fitness_equipment benchmark categories remain untested. Expanding the vendor set should be the pipeline's top priority.
- **Anker's Rakuten discovery enriches the Program Presence evidence** but doesn't change the score (2 major networks = score 2 per rubric). The UK Webgains discovery (7-12%, daily datafeed) adds depth to the niche network and commission evidence. A dedicated Anker re-scoring pass should incorporate both findings.
- **GRIN's free affiliate infrastructure** signals a structural shift in platform economics — if infrastructure becomes free, value migrates to intelligence and execution layers. This doesn't affect AFARE scoring but is strategically important for LiveChannel's competitive positioning.
- **No rubric changes made. No benchmark changes made. Methodology stable through week 4.**
