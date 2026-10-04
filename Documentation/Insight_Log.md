# AI Insight Sprint™ — Insight Log

## Purpose

The Insight Log provides evidence-to-insight traceability for material findings identified during Case Study #2.

## I-001 — Payment realization is low

**Finding:** Payment realization is low.

**Evidence:** Power BI Payment Ratio KPI and Revenue Intelligence analysis.

**Interpretation:** Only 40.03% of assessed revenue is recorded as paid.

**Implication:** Revenue realization is a primary management challenge.

**Recommendation:** Develop targeted recovery efforts focused on high-value outstanding assessments.

**Limitation:** The finding is based on recorded assessment and payment data.

---

## I-002 — No-payment assessments require attention

**Finding:** A significant number of assessment records have no payment record.

**Evidence:** Power BI No-Payment Assessments KPI and Compliance Intelligence analysis.

**Interpretation:** 11,242 assessment records have no payment record.

**Implication:** The volume requires collection and reconciliation review.

**Recommendation:** Conduct targeted review and recovery of no-payment assessments.

**Limitation:** A missing payment record does not automatically prove non-compliance.

---

## I-003 — Revenue is concentrated among larger taxpayers

**Finding:** Larger taxpayers contribute a disproportionate share of assessed revenue.

**Evidence:** Power BI Taxpayer Base and Assessed Revenue by Business Size.

**Interpretation:** Large taxpayers represent 14.98% of the taxpayer base but account for 33.83% of assessed revenue.

**Implication:** A relatively small taxpayer segment contributes a substantial share of assessed revenue.

**Recommendation:** Establish enhanced monitoring and follow-up for large taxpayers.

**Limitation:** The analysis describes concentration and does not establish causation.

---

## I-004 — Geographic recovery priorities differ

**Finding:** Revenue scale and outstanding exposure vary across states.

**Evidence:** Power BI state-level revenue and outstanding exposure analysis.

**Interpretation:** Lagos leads assessed revenue at approximately ₦2.74B, while Ogun has the highest outstanding exposure rate at 66.31%.

**Implication:** Recovery priorities may differ depending on both revenue volume and exposure rate.

**Recommendation:** Use both revenue volume and outstanding exposure when prioritizing geographic recovery activity.

**Limitation:** State-level patterns require further operational validation.

---

## I-005 — Payment reconciliation requires review

**Finding:** A substantial number of payment records occur before their linked assessment date.

**Evidence:** Python analysis and Power BI Payment Timing analysis.

**Interpretation:** 7,462 payment records occur before the linked assessment date.

**Implication:** The pattern requires reconciliation and operational review.

**Recommendation:** Review whether these records represent legitimate prepayments, posting or adjustment processes, or data-quality issues.

**Limitation:** The dataset alone cannot determine the operational reason for the timing pattern.

---

## Analytical Principle

The Insight Log follows the AI Insight Sprint™ principle:

**Evidence → Insight → Action → Decision**

Anomalies are treated as signals requiring validation rather than automatically being classified as errors or non-compliance.
