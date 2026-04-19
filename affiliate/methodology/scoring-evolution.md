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
