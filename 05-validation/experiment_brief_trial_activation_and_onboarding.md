# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

---

## 1. Choose the Method

**Method:** In-App A/B Test (50/50 Split)  
**Why:** FinWise cannot afford to leave initial onboarding to passive user exploration; historical data shows that users who fail to connect real financial data during their first session drop off rapidly and rarely return. An In-App A/B Test randomly assigns incoming trial users at the point of account creation to either the status quo setup flow or a guided live-sync wizard, providing strict causal isolation.

---

## 2. Define the Experiment

* **Experiment ID:** `EXP-2026-Q4-ONBD-BANK-SYNC-WIZARD`
* **Objective:** Drive early value realization to unlock conversion: Test whether guiding users through a live bank-connection wizard and automated first-session cash-flow scenario during onboarding increases initial engagement, driving higher trial-to-paid conversion and 30-day modeling retention.

### Hypothesis
> "If we guide trial users through a live-sync bank connection wizard paired with an automated first-session cash-flow scenario during onboarding, then Trial-to-Paid Conversion Rate and 30-Day Active Financial Modeling Usage % will increase because users experience immediate, real-time visibility into their actual business cash runway during their first session."

* **Primary Metric:** 30-Day Active Financial Modeling Usage % *(Leading indicator of core product engagement and value realization)*
* **Success Threshold:** Minimum Detectable Effect (MDE): Increase 30-Day Active Financial Modeling Usage % from the historical baseline average of 36.7% to $\ge$ 50.0% (a relative lift of $\ge 36\%$). Secondary monetization threshold: Lift Trial-to-Paid Conversion Rate from 1.99% to $\ge$ 3.00%.

---

## 3. Define What You're Testing

* **Current Experience (Control):** Status Quo Onboarding: An unguided, open-ended dashboard experience post-registration where users are left to manually upload CSVs, enter demo numbers, or locate bank integration settings on their own.
* **What You're Testing (Variant):** Guided Live-Sync Wizard: A compulsory 3-step wizard immediately following registration that prompts users to:
  1. Connect their primary business bank account via API.
  2. Select their target cash-flow runway threshold (e.g., 30/60/90 days).
  3. Auto-generate their first baseline cash-flow scenario using live data.
* **Invariant:** Pricing, marketing channels, trial duration (14 days), and core analytical features downstream remain identical across both groups.
* **Target Segment:** All newly registered trial users across web and mobile platforms during the 30-day experiment window.
* **Traffic Split:** 
  * **Control (50%):** Standard open-ended onboarding experience.
  * **Variant (50%):** Guided live-sync wizard experience.

---

## 4. Predict Your Outcome & Next Steps

* **Predicted Outcome:** 
  * *Primary Metric:* 30-Day Active Financial Modeling Usage % reaches $\ge$ 50.0% in the variant group.
  * *Secondary Metric:* Trial-to-Paid Conversion Rate rises to $\ge$ 3.00%.
  * *Guardrail Status:* Day-1 sign-up drop-off remains well within the +10% tolerance limit.
* **If Successful:** 
  * *Global Rollout:* Make the guided bank-sync wizard the default onboarding flow for 100% of new trial sign-ups.
  * *In-App Lifecycle Nudges:* Implement automated in-app prompts and email triggers at Day 3 and Day 7 for users whose sync connections drop or require credential refreshes.
  * *Extend Automation:* Test automated scenario template generation as Step 4 in the wizard (`EXP-2027-Q1-ONBD-SCENARIO-TEMPLATES`).
* **If Unsuccessful:** 
  * *Pivot to Pre-Built Demo Data:* Conclusively determine that upfront bank linking creates unacceptable setup friction for prospects.
  * *Test "Demo Vault" Sandbox:* Shift onboarding to pre-populated, realistic industry sandbox templates (`EXP-2027-Q1-ONBD-DEMO-VAULT`) allowing immediate scenario manipulation before requiring bank credential integration.

---

## Guardrails & Read Date

* **Guardrail Metrics:** 
  * Day-1 Onboarding Drop-Off / Abandonment Rate: Sign-up completion drop-off must not increase by more than 10% due to added friction.
  * Bank Sync Connection Error Rate: Failed API sync attempts must remain below 5% of total attempts.
* **Read Date:** 30 days post-launch (on Day 31, no earlier). No peeking.