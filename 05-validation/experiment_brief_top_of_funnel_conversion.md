# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

---

## 1. Choose the Method

**Method:** Channel-Segmented A/B Cohort Test  
**Why:** FinWise cannot afford to evaluate growth purely on aggregate trial volume; optimizing for top-of-funnel volume without measuring source quality actively burns marketing budget on low-intent users who leak out at a 98% non-conversion rate and a 60% annual churn rate. A Channel-Segmented A/B Cohort Test establishes true causal attribution between acquisition targeting criteria (independent variable) and downstream monetization/retention quality (dependent variables) while holding core product onboarding constant.

---

## 2. Define the Experiment

* **Experiment ID:** `EXP-2026-Q4-ACQ-INTENT-FIT-TEST`
* **Objective:** Determine whether reallocating marketing spend toward high-intent acquisition channels (e.g., targeted non-brand search and vertical-specific financial channels) improves user fit, thereby driving higher 30-day active financial modeling usage (core leading indicator) and lifting the overall Trial-to-Paid Conversion Rate past the 2% ceiling.

### Hypothesis
> "If we reallocate a portion of the paid acquisition budget from broad volume-focused campaigns to high-intent search and vertical-specific channels, then Trial-to-Paid Conversion Rate and 30-Day Active Financial Modeling Usage % will increase because we are acquiring users whose core operational needs match FinWise’s feature capabilities."

* **Primary Metric:** Trial-to-Paid Conversion Rate (%) *(The definitive measure of user-product fit and monetization viability)*
* **Success Threshold:** Minimum Detectable Effect (MDE): Lift Trial-to-Paid Conversion Rate from the historical 1.99% baseline to $\ge$ 3.50% for high-intent test cohorts (a relative lift of $\ge 75\%$). Secondary validation: 30-Day Active Financial Modeling Usage % $\ge 50\%$.

---

## 3. Define What You're Testing

* **Current Experience (Control):** Broad, volume-focused paid acquisition campaigns (e.g., broad-match social and display ads) optimized strictly for maximizing Trial Sign-up Volume. Inbound traffic is generic and unsegmented, leading to high upfront drop-off, lower intent, and a historical ~1.99% trial-to-paid conversion ceiling.
* **What You're Testing (Variant):** High-Intent Channel & Audience Reallocation. Reallocating 50% of the paid acquisition budget away from broad display/social channels into high-intent search queries (e.g., specific non-brand keywords like *"SaaS cash flow modeling tool"*, *"fractional CFO scenario software"*) and vertical-specific financial media channels.
* **Invariant:** The in-app product, onboarding flow, pricing, and 14-day trial mechanics remain 100% identical for all cohorts to isolate marketing channel intent as the sole variable.
* **Target Segment:** All new prospective users entering the FinWise acquisition funnel via paid channels during the 30-day experiment window.
* **Traffic Split / Allocation:** 
  * **Control Group (50%):** Paid traffic driven by existing broad-volume acquisition campaigns.
  * **Variant Group (50%):** Paid traffic driven by high-intent, vertical-focused search and targeted campaigns.

---

## 4. Predict Your Outcome & Next Steps

* **Predicted Outcome:** 
  * *Primary Metric:* High-intent variant cohort achieves a Trial-to-Paid Conversion Rate of $\ge$ 3.50% (surpassing the historical ~1.99% ceiling, representing a $\ge 75\%$ relative lift).
  * *Secondary Metric:* 30-Day Active Financial Modeling Usage % for the variant cohort rises to $\ge$ 50% (up from the historical baseline average of 36.7%).
  * *Guardrail Status:* Cost Per Paid Subscriber (Blended CAC) remains within the +15% threshold.
* **If Successful:** 
  * *Full Budget Reallocation:* Permanently retire low-intent, volume-driven display campaigns and reallocate 100% of paid acquisition spend toward high-intent search and vertical-specific financial media channels.
  * *Refine Messaging:* Launch follow-up experiment (`EXP-2026-Q4-ACQ-LANDING-FIT`) to test tailored landing page copy targeting high-converting search personas.
  * *Update Unit Economics:* Recalculate customer lifetime value (LTV) and CAC payoff periods using the 3.5%+ conversion baseline.
* **If Unsuccessful:** 
  * *Pivot Focus In-App:* Conclusively rule out acquisition targeting as the primary driver of the 2% ceiling; accept that users are hitting an in-app monetization wall.
  * *Execute Paywall Experiment:* Shift immediately to testing an in-app monetization hypothesis (`EXP-2027-Q1-MONETIZATION-GATING`), replacing the rigid 14-day trial with a value-milestone-gated trial.

---

## Guardrails & Read Date

* **Guardrail Metrics:** Cost Per Acquisition (CPA) / Cost Per Paid Subscriber must not increase by more than 15% overall. Total trial sign-up volume floor must not drop below 300 trials/month.
* **Read Date:** 30 days post-launch (on Day 31, no earlier). No peeking.