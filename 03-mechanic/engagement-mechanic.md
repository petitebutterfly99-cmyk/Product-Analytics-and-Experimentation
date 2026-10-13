# The Mechanic · FinWise Co. · Retention Mechanic & Habit Loop Specification

> Module 3 · Retention & Engagement. The engagement mechanic that builds the habit loop, with rationale and a wireframe.

## The mechanic

_The habit loop: trigger → action → reward → investment._

* **Mechanic Selected:** **Something new** (*Forecast Freshness & Risk Decay Engine*)
* **Type:** Custom Hybrid (Operational Status Indicator + Decay Curve + Value-Gated Freshness)
_____

| Stage | Mechanism | User Experience / Flow |
| :--- | :--- | :--- |
| **TRIGGER** | **External & Internal Triggers** | • **External:** Weekly Friday afternoon email/Slack prompt (*"Your 30-Day Cash Runway Forecast is 7 days old — 4 unreviewed vendor charges pending"*).<br>• **Internal:** Founder/SMB owner's weekly operational anxiety regarding payroll, upcoming bills, and cash availability for the following week. |
| **ACTION** | **Simple, Core Action** | The user logs into FinWise, clicks **"Refresh Feeds & Update Model,"** and spends 2 minutes reviewing/categorizing new automated bank transactions to reconcile their forward-looking cash-flow model. |
| **REWARD** | **Immediate Operational Relief & Status Boost** | • Visual feedback: The **Forecast Freshness Indicator** instantly shifts from Yellow/Red to vibrant Green (*"100% Fresh · High-Confidence Runway"*).<br>• Functional relief: An updated cash-runway graph confirming exact cash availability, eliminating financial blind spots. |
| **INVESTMENT** | **Compounding Product Value & Frictionless Routine** | The user fine-tunes a categorization rule or modifies a cash-flow scenario. This action makes the underlying AI engine smarter, deepens historical transaction accuracy, and increases the switching cost of leaving FinWise. |

## Rationale : Driving Pre-Paywall Retention & Addressing Churn

### Alignment with Churn Diagnosis
* **The Root Cause of Churn:** The 13-month dataset revealed that while users perform initial administrative tasks (`Import Data %`), engagement stalls before adopting forward-looking scenario modeling (`Modeling %`). Users convert during the reverse trial, stop updating their cash projections, lose visibility into future cash runway, and churn post-purchase due to perceived loss of value.
* **Why Traditional Mechanics Fail:**
  * **Daily Streaks** fail because SMB financial reviews naturally occur on a weekly cadence, making daily prompts feel artificial and annoying.
  * **Leaderboards** fail because financial runway and bank data are deeply sensitive and non-competitive.

### How "Forecast Freshness" Solves the Retention Problem
1. **Leverages Operational Risk over Artificial Gamification:** Instead of penalizing users with a meaningless score reset, the mechanic taps into natural loss aversion by showing **data staleness**. A business owner cares deeply when their cash-flow confidence score drops from 95% to 60%.
2. **Establishes the Weekly Operational Habit During the Reverse Trial:** By embedding the Freshness Decay loop (Green $\rightarrow$ Yellow $\rightarrow$ Red over 7 days) during the free trial, users form an indispensable weekly review habit *before* hitting the paywall cliff.
3. **Connects Habit to Monetization:** When the trial expires, the user isn't just paying to keep "access to software"—they are paying to maintain an active, high-confidence decision engine that protects their business from cash-flow surprises.
_____

## Wireframe

<img width="654" height="594" alt="image" src="https://github.com/user-attachments/assets/781b8852-875d-4445-92a4-f150c2bba8f6" />

_____

