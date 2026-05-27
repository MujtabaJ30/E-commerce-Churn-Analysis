# E-Commerce Retention Strategy

## Overview
Analyzed behavioral and transaction data from 50,000+ e-commerce users to identify why high-value customers churn.

The analysis showed churn was driven more by support friction and poor onboarding than pricing.

## Key Metrics
- **Churn Rate:** 28.9%
- **Revenue at Risk:** $20.6M (Customer LTV)
- **Average Order Value of Churned Users:** $134.76

---

# Key Insights

## 1. Support Friction Drives Churn
Customer churn increased sharply after **6 support calls**.

- Churn probability exceeded 40% beyond this point
- Repeated support interactions indicated unresolved issues
- High-value users were also affected

![Breaking Point](./images/breaking_point.png)

---

## 2. High-Value Customers Quietly Churned
RFM segmentation identified a group of high-spending users who gradually stopped engaging instead of contacting support.

- Reduced login activity was a strong churn signal
- Many churned users had high historical spend
- This segment represented the largest revenue risk

![Revenue at Risk](./images/revenue_at_risk.png)

---

## 3. Weak Mobile Adoption Increased Early Churn
New users with low mobile app usage were significantly more likely to churn within the first 90 days.

- App adoption strongly correlated with retention
- Email onboarding showed low engagement
- Early activation gaps predicted long-term churn

![Activation Gap](./images/activation_gap.png)

---

# Proposed Retention Strategy

## Phase 1: Reduce Support Friction
- Route users with AOV > $130 directly to senior support agents
- Trigger proactive recovery offers after the 4th support call
- Reduce escalation loops and unresolved tickets

## Phase 2: Improve Early Activation
- Shift onboarding from email-heavy flows to SMS/push notifications
- Increase mobile app adoption during the first 90 days
- Focus onboarding around early engagement actions

---

# Tech Stack
- **Python:** Pandas, Matplotlib, Seaborn
- **Methods:** RFM Segmentation, Cohort Analysis
