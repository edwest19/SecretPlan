# Medicare Part D Prescription Plan Analysis Prompt

## Purpose

This example uses entirely fictional information to demonstrate how to complete the template.

---

# Privacy Notice

No real person or identifying information is used in this example.

---

# Applicant Information

| Field | Value |
|---------|---------|
| ZIP Code | 11743 |
| County | Suffolk |
| State | NY |
| Age | 72 |
| Current Medicare Coverage | Original Medicare |
| Extra Help (LIS) Status | No |
| Other Coverage | None |
| Analysis Year | 2027 |
| Enrollment Decision For | Next Year |

Optional:

| Field | Value |
|---------|---------|
| Income Range | $50,000 - $75,000 |
| Additional Notes | Travels occasionally within New York State |

---

# Prescription List

| Medication | Brand or Generic | Strength | Quantity Per Fill | Days Supply / Directions |
|------------|-----------------|-----------|-------------------|--------------------------|
| Atorvastatin | Generic | 40 mg | 90 | Once daily |
| Lisinopril | Generic | 20 mg | 90 | Once daily |
| Eliquis | Brand | 5 mg | 60 | Twice daily |
| Levothyroxine | Generic | 100 mcg | 90 | Once daily |
| Jardiance | Brand | 25 mg | 30 | Once daily |

---

# Pharmacy Preferences

## Pharmacy Ranking

| Rank | Pharmacy | City | Will Use? |
|--------|------------|-------|----------|
| 1 | Costco | Commack | Yes |
| 2 | CVS | Huntington | Yes |
| 3 | Walgreens | Huntington Station | Yes |
| 4 | Express Scripts Mail Order | N/A | Maybe |

## Pharmacy Flexibility

| Preference | Response |
|------------|----------|
| Willing to Switch Pharmacies? | Yes |
| Willing to Use Mail Order? | Maybe |
| Requires Local Pickup? | Yes |
| Pharmacies to Avoid | None |

---

# Coverage Goals

Rank priorities from 1 (most important) to 5 (least important).

| Priority | Rank |
|-----------|------|
| Lowest Total Annual Cost | 1 |
| Lowest Monthly Premium | 5 |
| Lowest Pharmacy Cost | 2 |
| Keep Current Pharmacy | 3 |
| Keep Current Medications Covered | 1 |
| Avoid Mail Order | 4 |
| Convenience | 4 |

Additional goals:

The applicant wants predictable prescription costs and does not want to discover after enrollment that a medication is not covered.

---

# Future Medication Flexibility

How important is future drug coverage flexibility?

- [x] Very Important
- [ ] Somewhat Important
- [ ] Not Important

The applicant is concerned that additional medications may be prescribed during the coming years and wants plans with broader formularies and fewer utilization restrictions.

---

# Tie-Breaker Rules

When two plans appear similar, break ties in this order:

1. Lowest verified annual cost
2. Better coverage of current medications
3. Better pharmacy access
4. Broader formulary
5. Fewer utilization restrictions
6. Higher CMS Star Rating

---

# Research Instructions

## Location Notes

Analyze Medicare Part D prescription drug plans available to:

- ZIP: 11743
- County: Suffolk
- State: New York
- Plan Year: 2027

Use official Medicare and plan documents whenever available.

---

# Special Questions

Please answer the following in addition to the standard analysis:

1. Are any current medications subject to prior authorization, quantity limits, or step therapy?
2. Does Costco provide preferred-network pricing under the recommended plans?
3. Does mail order provide meaningful savings?
4. Which plans appear to provide the best protection if a new expensive medication is prescribed during the year?
5. Does New York EPIC appear relevant for this applicant's situation?
6. What assumptions would most likely change the recommendation?

---

# Required Report Format

## Executive Summary

Provide a plain-English summary suitable for a Medicare beneficiary.

---

## Applicant Inputs and Assumptions

List all assumptions made.

---

## Available Plans

Provide a comparison table that includes:

- Premium
- Deductible
- CMS Rating
- Pharmacy Network Structure
- Mail Order Availability

---

## Drug Coverage Comparison

Provide:

- Coverage status
- Tier
- Restrictions
- Generic availability

for every medication under every recommended plan.

---

## Annual Cost Comparison

Provide estimated:

- Premium costs
- Deductible costs
- Prescription costs
- Total annual costs

Explain assumptions.

---

## Pharmacy Comparison

Compare:

- Costco
- CVS
- Walgreens
- Mail Order

for every recommended plan.

---

## Cash Price Comparison

Compare Part D costs against available cash pricing for:

- Atorvastatin
- Lisinopril
- Eliquis
- Levothyroxine
- Jardiance

when verifiable pricing is available.

---

## Medicare Rules Summary

Explain current Medicare Part D rules relevant to the selected plan year.

---

## Ranked Recommendations

Provide:

1. Best Overall Plan
2. Lowest Total Cost Plan
3. Best Pharmacy Choice
4. Best Long-Term Flexibility Choice

Clearly indicate whether recommendations are definitive or provisional.

---

## Confidence Rating

For each recommendation assign:

- High
- Medium
- Low

and explain the reason.

---

## Sources

Provide direct citations and links to:

- Medicare.gov
- CMS
- Plan formularies
- Pharmacy directories
- Pricing sources

Include dates checked.

---

# Quality Requirements

- Use current plan-year information.
- Cite all sources.
- Distinguish facts from assumptions.
- Distinguish verified data from estimates.
- Never invent coverage information.
- Explain uncertainty when information cannot be verified.