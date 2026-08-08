# FinWise · Hypothesis & Bet, Module 1

## Exercise 1 · First hypothesis
- **Hypothesis:** I think FinWise's biggest problem is that paid acquisition is optimized for trial volume, not trial fit — so as spend scales, it pulls in lower-intent users who were never likely to convert or stay, which explains both the acquisition plateau and the low conversion/high churn numbers.
- **Evidence:** **Most of the marketing budget goes to paid acquisition to drive trial sign-ups — a volume-focused strategy.
**Adding more acquisition spend is no longer producing meaningful growth, suggesting diminishing returns on the current targeting approach, not just a saturated market.
**Low trial-to-paid conversion (2%) and high one-year churn (60%) both sit on the "does this user actually fit the product" side of the funnel, which acquisition targeting — not onboarding — most directly controls.
- **Bet:** The one thing I'd test first is whether trial-to-paid conversion and one-year retention vary meaningfully by acquisition source or campaign.

## Testable hypothesis
- **IF** we segment trial starts by acquisition source and compare trial-to-paid conversion and retention across segments:
- **THEN** conversion and retention WILL VARY substantially (2x or more) between sources, even though the blended averages sit at 2% conversion and 40% retention:
- **BECAUSE** acquisition is currently optimized for cost-per-trial rather than cost-per-paying-customer, so a mix of high-fit and low-fit traffic is being blended into one flat, low-looking number.
- **MEASURED WITH** a retrospective cohort pull joining trial starts to acquisition source, calculating trial-to-paid conversion and one-year retention per source, done within days since it uses existing historical data rather than a live test.

## Hands-On Lab · Pressure-test
- **Most surprising pattern:** Most surprising pattern: the fixed $78,125 revenue-per-paid-customer

Across all 13 months, revenue divided by paid customers returns exactly $78,125 every single time — whether there were 6 paid customers or 13. This is the most surprising finding because it's a level of precision you don't normally see in real-world SaaS data, where pricing tiers, discounts, add-ons, or timing of billing cycles would typically introduce at least some variation month to month. Zero variance across 13 independent months stands out more than any of the funnel or adoption metrics, which all show normal-looking fluctuation.
- **Biggest drop-off stage:** Revenue
- **Verdict:** Challenged
- **What the data told me:** What the data told me: Trial volume and trial-to-paid conversion don't move together, so the "more volume dilutes fit" mechanism doesn't hold up.

The specific data point: June 2024 has both the lowest trial count (321) and the lowest conversion rate (1.87%) — same direction, not inverse. March 2024 has the highest trial count (644) and converts at 2.02%, near the average. Across all 13 months, conversion stays flat (1.87%–2.08%) regardless of volume.

My updated thinking: Conversion looks like a flat, structural rate rather than something that responds to volume. This doesn't rule out acquisition quality as a factor — that still needs channel-level data — but it does rule out volume itself as the mechanism. The real volatility is upstream, at Visits → Trials.

## My bet
- **Growth loop:** Collaboration
- **Reasoning:** I would experiment with a collaboration loop because financial software naturally requires a second stakeholder — an accountant or bookkeeper — making invites a built-in step rather than an optional ask. This directly targets the plateaued acquisition problem by generating new trials from product usage itself, without relying on more paid ad spend.
- **Formalized:** FinWise's biggest growth problem is FinWise's growth has plateaued because acquisition spend is no longer producing meaningful new trial volume, and the company has no channel for generating trials that doesn't depend on that spend. because Financial software naturally involves a second stakeholder — an accountant or bookkeeper — who business owners need to loop in to actually use the product, but FinWise currently has no step in onboarding that prompts users to invite them, leaving that built-in growth surface untapped., and the highest-leverage experiment I'd run first is Add an "invite your accountant/bookkeeper" prompt during account setup, before the trial ends. Run as an A/B test on new sign-ups over 4–6 weeks — treatment sees the invite prompt, control doesn't. Primary metric: trial-to-paid conversion rate (invite-sent vs. no-invite segments) and number of new trials originating from invited collaborators. Guardrail: time-to-first-core-action, to confirm the prompt doesn't add friction..
