
Digital Marketing Anomalies Detection

This Notebook analyzes marketing conversion data, identifies anomalies, and highlights unusual trends in key performance metrics. It helps detect irregularities in conversion rates that may indicate fraud, tracking issues, or unexpected user behavior.

📌 Data Preprocessing

Loads and formats marketing data.
Groups data into 2-day intervals for trend analysis.
Metric Calculation

Computes IPM (Installs per 1000 Impressions), CPM (Clicks per 1000 Impressions), and Click2Action (Conversions per Clicks).
Applies log transformation for better data distribution.
Anomaly Detection

Uses probability-based methods to compare metric values with historical medians.
Flags anomalies where deviations are statistically significant.
Insights & Visualization

Generates structured reports on detected anomalies.
Plots metric trends with highlighted min/max values.
(Optional) Telegram Alerts

Sends automated messages summarizing anomalies.

📂 Repository Contents
convesions_anomalies_detection.ipynb – Jupyter Notebook for data processing and anomaly detection.
conversions_data.csv – Sample dataset for testing.
README.md – Documentation.

📌 Notes
The dataset is sample data for testing.
Thresholds and probability calculations may need adjustments for different datasets.
Telegram alerts require valid API credentials.
