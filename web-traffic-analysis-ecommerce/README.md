# 📊 Web Traffic & User Behavior Analysis (E-commerce)

This project analyzes web traffic from the Google Merchandise Store (GA4 public dataset) using BigQuery and Python. It identifies underperforming landing pages, bounce rate patterns, and simulates A/B testing to evaluate potential improvements.

## 📌 Objective
Analyze user sessions to:
- Identify high-bounce traffic sources and device types
- Detect underperforming landing pages
- Simulate A/B testing to test design improvements

## 🛠️ Tools & Technologies
- **Google BigQuery** (GA4 Sample Dataset)
- **Python** (Pandas, Seaborn, NumPy, SciPy, Matplotlib)
- **SQL**
- **A/B Testing (Simulated)**

## 📈 Key Insights
- Direct and Referral traffic sources had the highest bounce rates
- Mobile users bounced more frequently than desktop users
- Identified 3 landing pages with bounce rates over 80%
- Simulated A/B testing showed a 12% projected increase in conversion rate (statistically significant)

## 📊 Visualizations
| Metric                          | Chart Preview |
|-------------------------------|----------------|
| Bounce Rate by Traffic Source | ![Bounce Rate by Source](bounce_rate_by_source.png) |
| Bounce Rate by Device Type    | ![Bounce Rate by Device](bounce_rate_by_device.png) |
| A/B Test Result Comparison     | ![A/B Test Result](ab_test_results.png) |
| Pageviews vs Bounce Rate       | ![Scatter Plot](scatter_pageviews_bounce.png) |

## 📁 Dataset
- **Source:** [Google Analytics Sample - BigQuery](https://console.cloud.google.com/marketplace/product/bigquery-public-data/google-analytics-sample)
- **Date Range Used:** 1st August 2016 – 10th August 2016
- **Sessions Analyzed:** 10,000+

## ✅ Outcomes
- Data-driven insights delivered through Python visualizations
- Improved understanding of traffic sources, device usage, and bounce behaviors
- Demonstrated A/B testing using simulated data with statistical validation

---

## 💡 Author
**Arjun Athrey**  
*Data Analyst in training | Python | SQL | Web Analytics*