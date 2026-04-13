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
