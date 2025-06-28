# Simulating Payout Policy Changes:  
## How Lower Payout Thresholds Can Impact Small Creator Earnings & Retention

---

## Project Overview

This project explores how lowering the minimum payout threshold for creators on a digital content platform could impact their average earnings and retention. Many online platforms pay creators once they reach a certain minimum threshold (for example, $100). For smaller creators, reaching this threshold can take months delaying their payouts and potentially affecting their motivation to keep producing content.

This project uses simulated data to estimate the **causal effect** of lowering the payout threshold using a **Difference-in-Differences (DiD)** approach — a common method for measuring policy impacts when random A/B testing may not be practical.

---

## Business Context

Many creator platforms (streaming services, digital marketplaces) set payout thresholds to limit transaction costs and simplify payment processing. But a higher threshold can create cash flow delays for smaller creators, leading to potential frustration and churn.

A product or payments team might ask:  
**“What would happen if we lowered our payout threshold from $100 to $50? Would more small creators stay active? Would it meaningfully increase their monthly income?”**

---

## Why Not A/B Test This?

Unlike simple feature tests, payout policy changes directly affect real money, so randomizing who gets paid sooner vs. later is often impractical or unfair. Instead, platforms often roll out the policy universally, then use quasi-experimental methods like Difference-in-Differences to measure its impact.

---

## Project Goals

- Simulate realistic monthly payout data for 1,000 creators over 12 months.
- Create cohorts: small creators likely affected vs. larger creators unlikely to be affected.
- Simulate a policy change in mid-year that lowers the payout threshold.
- Apply Difference-in-Differences to estimate the impact on earnings and retention.
- Visualize trends and results using **Python** and **Tableau**.
- Deliver a clear one-page memo summarizing findings.

---

## Methodology

 **Data Simulation**  
- 1,000 creators with unique earning levels, streaming hours, viewer counts, and regions.
- Monthly earnings fluctuate naturally.
- Small creators earning $50–$100 per month are the **treated group** — they benefit from the new lower threshold.
- Larger creators earning $100–$150 are the **control group** — already above the threshold, so mostly unaffected.
- After the policy change mid-year, treated creators receive a simulated **10% earnings boost** to mimic earlier payouts encouraging more activity.

 **Analysis**  
- Use Python (`Pandas`, `NumPy`) for simulation and cohort tagging.
- Apply **Difference-in-Differences** logic to estimate the average treatment effect.
- Visualize trends over time using `Matplotlib` and `Seaborn`.
- Export the dataset to CSV for **Tableau** dashboards.

---

## Why This Matters

This project shows how to **measure policy impact** in situations where traditional A/B testing is not feasible. It demonstrates practical **causal inference** skills that are valuable for roles in product analytics, payments, policy measurement, and marketplace data science.

---

**Thanks for reading!**
