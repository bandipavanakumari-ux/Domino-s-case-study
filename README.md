# Domino-s-case-study
Project Overview

This project analyzes food delivery time data to check whether a Domino’s franchise store is at risk of violating SLA (Service Level Agreement) rules.

 ### SLA Condition:

95th percentile of delivery time must be below 31 minutes
Failing this could lead to franchise cancellation.

As part of my Data Science Internship, I used Python and statistical analysis to evaluate the risk and provide data-driven recommendations.

### Business Problem

Average delivery time looked good

But management received a warning based on 95th percentile performance

 ### Key Question:
Is the store actually violating the SLA, or is it safe for now?

### Dataset

Real-world delivery time data (in minutes)

Each row represents one completed order

 ### Analysis Performed

1.Data cleaning & exploration

2.Distribution analysis

3.Percentile calculations (P90, P95)

4.Outlier impact analysis

5.Business-focused interpretation

 ### Key Findings

95th percentile delivery time: 27.26 minutes → SLA met ✅

~3.7% of orders exceed 31 minutes 

##### Average delivery time: ~16 minutes

Few delayed orders heavily impact percentile-based SLAs

 ### Key Insight

 Averages can be misleading. Percentiles show real risk.

### In SLA-driven businesses:

 1.Outliers matter more than fast deliveries

 2.A small number of delays can push the 95th percentile beyond limits

### Recommendations

1.Monitor P90 & P95 delivery times daily

2.Set alerts for orders crossing 25 minutes

3.Improve staffing during peak & late-night hours

4.Track delivery-partner-wise delays

### Tools & Technologies

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

 ### Conclusion

This project shows how data science helps businesses stay compliant, identify risks early, and avoid penalties — even when averages look good.
