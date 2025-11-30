📊 Funnel & Conversion Analytics Project
🔍 Overview

This project analyzes the player journey across key stages—Registration → First Deposit → First Bet → 30-Day Activity—to identify conversion performance, drop-off points, engagement patterns, and revenue concentration. The goal is to uncover insights that help optimize acquisition, retention, and monetization strategies.

🧹 Data Preparation

Cleaned and transformed raw datasets for consistency and analysis.

Merged multiple data sources using unique player IDs.

Handled missing values, date formats, and derived new metrics (e.g., days active, time gaps).

📈 Key Analyses
1. Funnel & Conversion Metrics

Built a complete funnel tracking players through four lifecycle stages.

Calculated conversion percentages at each stage.

Identified the stage with the largest drop-off using acquisition channel and cohort comparisons.

2. Retention & Engagement

Measured active days for the first 30 days after registration.

Grouped players into activity cohorts (1–2 days, 3–5, 6–10, etc.) to understand retention quality.

Calculated time gap between first deposit and first bet.

Analyzed mean, median, percentile distributions to interpret engagement tendencies.

3. Player Segmentation

Identified top 10% high-value players based on total deposits.

Measured their share of total deposits to assess revenue concentration.

Binned first deposit amounts into ranges to visualize clustering behavior.

📊 Visualizations

Funnel charts for stage-wise conversion.

Cohort activity and retention heatmaps.

Distribution plots for deposit → bet time gaps.

Bar and histogram visualizations for deposit amount clusters.

🛠️ Tools & Technologies

Python (pandas, numpy, matplotlib, seaborn)

Power BI / Excel (for dashboard views, if applicable)

Jupyter Notebook

SQL (optional for preprocessing)

🎯 Insights Summary

Identified the most impactful drop-off stage in the player funnel.

Cohort analysis revealed which engagement groups drive the majority of deposits.

Time-gap distribution showed how early betting correlates with higher retention.

Top 10% players contributed a significant share of deposits, reflecting high revenue concentration.

Deposit amount clustering exposed patterns useful for segmentation and profitability prediction.

📁 Project Structure
├── data/                 # Raw and cleaned datasets  
├── notebooks/            # Jupyter notebooks for analysis  
├── visuals/              # Generated charts and funnel visuals  
├── scripts/              # Python scripts (if modularized)  
└── README.md             # Project documentation  

🚀 Future Enhancements

Predict churn probability using machine learning.

Build an automated Power BI dashboard for real-time funnel tracking.

Introduce LTV (Lifetime Value) modelling.

Add RFM segmentation for deeper player profiling.

🤝 Contributions

Feel free to open issues or submit pull requests to improve analysis or visualizations.
