📊 Insurance Claims & Fraud Analysis
📌 Project Overview

This project explores insurance claims data through Exploratory Data Analysis (EDA) to identify patterns and indicators of fraudulent activity. Fraudulent claims are a major concern for insurers, leading to heavy financial losses. By analyzing claim behavior across demographics, policy details, and reporting practices, the project provides actionable insights that can support fraud detection and risk management.

🎯 Objectives

Identify fraud indicators using statistical and visual analysis.

Compare fraud vs. non-fraud claims across customer and policy attributes.

Detect anomalies in claim amounts and reporting behavior.

Provide insights to support the development of fraud detection models.

🗂️ Dataset

Source: Insurance claims dataset (CSV file).

Key Features:

Claimant demographics (age, gender, income, education).

Claim details (claim amount, policy premium, policy type).

Fraud report status (fraud_reported).

External reporting (police_report_available, authorities_contacted).

🔍 Exploratory Data Analysis

The project applies statistical checks, missing value handling, and visualization techniques to reveal hidden patterns.

Key Visualizations & Insights:

Missing Value Analysis – Missingness concentrated in reporting fields, suggesting behavioral fraud signals.

Fraud vs. Non-Fraud Distribution – Fraud cases form a minority but have significant financial impact.

Boxplots & Histograms – Fraudulent claims show higher amounts, more outliers, and skewed distributions.

Police Report & Authority Analysis – Absence of reports strongly correlates with fraud.

Scatter Plots (Age vs Claim / Premium vs Claim) – Fraudulent claims break expected relationships, creating anomalies.

Average Claim by Age – Fraud inflates averages across multiple age groups.

Correlation Heatmap – No single variable explains fraud; patterns emerge only in combination.

📈 Key Findings

Fraudulent claims are inflated and irregular compared to genuine ones.

No police report or authority involvement is a strong fraud indicator.

Fraudsters often break logical trends (e.g., premium-to-claim ratios).

Fraud is spread across demographics, though some age ranges show higher risk.

Multivariate analysis is essential; fraud cannot be detected using single-variable thresholds.

✅ Conclusion

The analysis highlights that while fraudulent claims are fewer, they are identifiable through systematic data analysis. Insurers should focus on:

Monitoring claim-to-premium ratios.

Flagging claims without authority reports.

Applying multi-feature fraud detection models.

These insights provide a foundation for building predictive fraud detection systems, reducing losses, and ensuring fairness for genuine policyholders.

⚙️ Tools & Libraries

Python: pandas, numpy

Visualization: matplotlib, seaborn, plotly

Missing Value Analysis: missingno

ML Preprocessing: sklearn (PCA, scaling)

📌 Author

Saumya Singh
