# Simulating Payout Policy Changes  
### How Lower Payout Thresholds Can Impact Small Creator Earnings & Retention  

---

##  Overview  

This project explores how lowering the minimum payout threshold (e.g., $100 → $50) could affect small creators’ **earnings and retention**.  

I chose this topic because smaller creators often wait months to hit payout minimums delaying their income and motivation. This simulation models how a lower threshold might improve engagement and earnings using a **Difference-in-Differences (DiD)** approach.

---

##  Key Insights  

- **Simulated** 1,000 creators over 12 months (earnings, activity, region).  
- **Treated Group:** Small creators earning $50–$100/month.  
- **Control Group:** Larger creators earning $100–$150/month.  
- After the mid-year policy change, treated creators’ average earnings rose by **$8–$10/month** while maintaining **~100% activity**.  
- Control group stayed flat → suggests **earlier payouts improve engagement** without hurting performance.

---

##  Visualization  

👉 [**Tableau Dashboard – Policy Impact on Creator Earnings (2023)**](policy_impact_db.twbx)  

![Policy Impact on Creator Earnings (2023)](DiD_policypayoutchange.png)

---

##  Tools Used  

**Python:** `pandas`, `numpy`, `matplotlib`, `seaborn`  
**Visualization:** Tableau  
**Method:** Difference-in-Differences (Causal Inference)

---

##  Conclusion  

Lowering the payout threshold increased small creator earnings by roughly **10%** without reducing activity rates.  
This suggests that **earlier payouts can enhance creator satisfaction and retention** at minimal risk to platform performance — a valuable insight for product and payments teams designing creator monetization policies.

##  Why It Matters  

This project demonstrates how **causal analysis** can guide **real-world policy changes** when A/B testing isn’t possible, blending product strategy, analytics, and data science to make platforms fairer for small creators.
