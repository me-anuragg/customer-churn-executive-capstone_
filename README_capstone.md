# Customer Churn Executive Analytics Capstone

## Deliverables
- `customer_churn_executive_capstone.pptx` — 8-slide executive presentation.
- `executive_findings.csv` — five decision-relevant descriptive findings and caveats.
- `churn_cleaning_log.csv` — reproducible basic data-quality checks.
- `customer_churn_sample.csv` — include the supplied source dataset when publishing the project.

## Executive question
Which customer groups should a fictional subscription team contact first to reduce avoidable churn?

## Method
Used the supplied 15-row CSV as provided. Checked missing cells, duplicate customer IDs, and basic impossible numeric values. No rows were removed. Findings are descriptive cross-tabs and group averages; no prediction or causal inference is claimed.

## Main recommendation
Pilot proactive retention outreach for month-to-month customers in their first six months, with service-recovery review for customers with high recent support-ticket counts. Use a holdout group and measure 30-day churn before scaling.

## Impact scenario (not a forecast)
Assume a 5–15 percentage-point absolute churn reduction versus holdout. Per 100 eligible customers, that would imply 5–15 additional retained customers if the effect is real. Using the sample's Basic monthly charge of ₹49.99 gives ₹250–₹750 in one month of gross billings. This is not profit, LTV, or a causal estimate.

## Limitations
- Very small synthetic sample (n=15), so rates are highly unstable.
- Contract, plan, tenure and payment method overlap; confounding is likely.
- No dates, churn reasons, intervention history, cost/margin, or representative sampling information.
- The uploaded dataset columns differ from the simplified field list in the task guide.

## Reproduce
Install Python with pandas and python-pptx, then run your analysis script on the supplied CSV. The cleaning log records the checks and whether rows were removed. Keep the source CSV with the deck when publishing.

## Publish one proof link
Upload the deck, source CSV, findings CSV, cleaning log and this README to one GitHub repository or view-only Drive folder. Confirm the link opens in a private/incognito window before submitting.
