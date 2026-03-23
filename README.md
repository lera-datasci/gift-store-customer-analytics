Customer Analytics Project
Overview

This project analyzes customer behavior, engagement, and revenue patterns using transactional data.
The goal was to identify key drivers of activity, segment customers, and validate hypotheses about user behavior.

🧹 Data Preparation
Merged multiple source datasets into a single analytical table
Removed duplicates and missing values
Filtered outliers using boxplot-based inspection
Selected 2019 as the primary analysis period (highest activity)
📈 Exploratory Analysis
Key findings
2019 was the peak activity period
Weekly and daily activity show high variability
No clear monthly seasonality detected
Unique users fluctuate significantly over time
Customer stickiness remained stable at ~5% (Q2–Q3)

👉 Insight: engagement is low but consistent → retention problem rather than volatility

👥 Customer Segmentation (RFM)
Two dominant segments were identified:
Champions (RFM: 333) — 651 users
Loyal (RFM: 233) — 326 users

👉 Insight:
A strong core user base exists, but growth likely depends on improving mid-tier user retention.

🧪 Hypothesis Testing
1. Retention differences (Q2 vs Q3)
→ No statistically significant difference

2. Average order value across countries (3, 6, 24)
→ No statistically significant difference

3. Second purchase > first purchase
→ Hypothesis not confirmed

👉 Insight:
User behavior is relatively stable across segments and geographies — no strong differentiators detected.

🧠 Key Insights
Activity fluctuates short-term but lacks long-term seasonality
Retention is low but stable (~5%)
Core value comes from Champions and Loyal users
No strong statistical differences across cohorts or countries
Increasing second purchase value is not supported by data

🚀 Recommendations
Focus on retention improvement, not just acquisition
Develop strategies targeting mid-tier users (between new and loyal)
Investigate drivers of low stickiness (~5%)
Test interventions via controlled experiments (A/B tests)
Improve tracking to better capture user lifecycle dynamics

🛠️ Tools & Methods
Python (pandas, numpy, scipy, matplotlib, seaborn)
RFM segmentation
Statistical hypothesis testing
Exploratory data analysis
