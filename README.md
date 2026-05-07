<div align="center">

# 🚀 Data Science & AI Portfolio
### Busra Zumrut Cevik
**Software Engineer • M.Sc. Student in Artificial Intelligence & Data Science**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/busra-cevik/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/busracevik)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black)](https://leetcode.com/u/B_SRA/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:busrazcvik@outlook.com)

</div>


## About Me

I'm a Software Engineer currently pursuing a Master's degree in Artificial Intelligence and Data Science at Politechnika Częstochowska (Poland). I've been building a structured portfolio of projects — starting from fundamental data analysis with **NumPy** and progressing to more advanced analyses using **Pandas**, with a clear roadmap ahead toward **Machine Learning** and **Deep Learning**.

I have worked on real-world datasets, applying analytical thinking and documenting my work with clear explanations and visual reports. I'm currently working on a **thesis project focused on predictive modeling of aircraft engine degradation** using machine learning and explainable AI (XAI), based on NASA datasets.

> 🎯 **Goal:** To grow as a software engineer specializing in Artificial Intelligence and Data Science.

---

## 🛠️ Skills

| Category | Technologies |
|---|---|
| **AI & Data Science** | Python, NumPy, Pandas |
| **Data Analysis & Processing** | Data Cleaning, Feature Engineering, EDA |
| **Data Visualization** | Matplotlib, Seaborn, Plotly |
| **Tools & Version Control** | Git, GitHub |
| **Learning Focus** | Machine Learning, Deep Learning, Predictive Modeling |

---

## 🗺️ Project Roadmap

```
From Fundamentals to AI and Data Science
─────────────────────────────────────────────────────────────────────
 NumPy       NumPy         NumPy         NumPy          NumPy         NumPy
 Basics   Earthquake     Climate      Time Series    Microsoft    Student Score
           Analyzer      Analyzer   Anomaly Detect  Stock Anomaly   Analysis
────────────────────────────────────────────────────────────────────
 Pandas      Pandas        Pandas        Pandas         Pandas        Pandas
 Basics    Global Eco   Customer       Medical       E-Commerce   Manufacturing
           Indicators     Churn        No-Show       RFM & Cohort   Downtime
─────────────────────────────────────────────────────────────────────
  ↓
 [Machine Learning] → [Deep Learning] → [XAI / Predictive Modeling]
```

---

## 📁 Projects

---

### 🔵 NumPy — Fundamentals

---

#### 1. NumPy Basics
> *Building the foundation of numerical computing*

**Overview:** Covers core NumPy operations and concepts that form the foundation of data analysis in Python.

**Key Concepts:**
- Array creation and manipulation
- Indexing and slicing
- Mathematical operations
- Aggregation functions
- Broadcasting

🔗 [View Repository](https://github.com/BusraCevik/numpy_basics)

---

#### 2. NumPy — Earthquake Analyzer
> *Real-world seismic data analysis*

**Overview:** Analyzes real-world earthquake data to explore patterns in magnitude, depth, and distribution using NumPy numerical operations.

**Key Concepts:**
- Data cleaning and preprocessing
- Handling missing values and outliers
- Time series analysis (earthquakes per year)
- Magnitude vs depth analysis
- Data visualization (histograms, scatter plots, interactive maps)

**Key Insights:**
- 🌍 Most earthquakes occur at lower depths, with magnitudes concentrated in moderate ranges
- 📍 Earthquake activity is concentrated along tectonic plate boundaries (Pacific Ring of Fire)
- 🔵 Shallow earthquakes are more frequent than deep ones

**Example Outputs:**

| Magnitude vs Depth (2D Histogram) | Magnitude vs Depth (Scatter) |
|---|---|
| ![hist](https://github.com/BusraCevik/numpy-earthquake-analyzer/blob/main/data/outputs/hist_depth_mag.png) | ![scatter](https://github.com/BusraCevik/numpy-earthquake-analyzer/blob/main/data/outputs/scatter_depth_mag.png) |

🔗 [View Repository](https://github.com/BusraCevik/numpy-earthquake-analyzer) · 🔴 [Live Dashboard](https://busracevik.github.io/numpy-earthquake-analyzer/)

---

#### 3. NumPy — Climate Analyzer
> *Global temperature trends & anomaly detection*

**Overview:** Analyzes climate data using NumPy to explore temperature trends and variations over time, applying linear regression for global warming trend detection.

**Key Concepts:**
- Statistical analysis (mean, standard deviation, variance)
- Yearly temperature aggregation and trend analysis
- Linear regression for global warming trend detection
- Climate anomaly detection using statistical thresholds
- Identification of extreme years (hottest and coldest)

**Key Insights:**
- 📈 Clear upward trend in global temperatures, especially in recent years
- ⚠️ Temperature anomalies concentrated in earlier periods of the dataset
- 🌡️ Combined trend + statistical threshold analysis reveals both long-term and unusual variations

**Example Outputs:**

| Yearly Anomalies | Yearly Summary |
|---|---|
| ![](https://github.com/BusraCevik/numpy-climate-analyzer/blob/main/data/outputs/yearly_anomalies.png) | ![](https://github.com/BusraCevik/numpy-climate-analyzer/blob/main/data/outputs/yearly_summary.png) |

🔗 [View Repository](https://github.com/BusraCevik/numpy-climate-analyzer) · 🔴 [Live Dashboard](https://busracevik.github.io/numpy-climate-analyzer/)

---

#### 4. NumPy — Time Series Anomaly Detection
> *Z-score based anomaly detection on synthetic data*

**Overview:** Detects anomalies in time series data using NumPy by analyzing deviations from expected behavior. Uses Z-score based statistical thresholding.

**Key Concepts:**
- Synthetic time series generation (trend, noise, injected anomalies)
- Z-score based anomaly detection
- Statistical thresholding using mean and standard deviation
- Optional smoothing (moving average)
- Identification of extreme values in time series

**Key Insights:**
- 📊 Clear upward trend detected, with anomalies primarily at the extreme ends of the distribution
- ✅ Z-score approach provides a solid, interpretable baseline before advancing to ML methods

**Example Outputs:**

| Detected Anomalies |
|---|
| ![](https://github.com/BusraCevik/numpy-time-series-anomaly-detection/blob/main/outputs/plots/anomalies_detected.png) |

🔗 [View Repository](https://github.com/BusraCevik/numpy-time-series-anomaly-detection/tree/main) · 🔴 [Live Dashboard](https://busracevik.github.io/numpy-time-series-anomaly-detection/index.html)

---

#### 5. NumPy — Microsoft Stock Price Anomaly Detection
> *Comparing multiple anomaly detection methods on financial data*

**Overview:** Analyzes Microsoft stock price data using multiple statistical methods (Z-score, Rolling Mean, IQR, EWMA) and compares their performance using precision, recall, and F1-score.

**Key Concepts:**
- Time series analysis in financial data
- Z-score, Rolling Mean, IQR, EWMA anomaly detection
- Comparative evaluation (Precision, Recall, F1-score)
- Detection of trend-based and contextual anomalies

**Key Insights:**
- 📈 Clear upward trend in stock prices; anomalies concentrated in high-volatility periods
- 🔍 Z-score & IQR highlight extreme values; Rolling Mean & EWMA catch contextual anomalies
- 📊 Comparative metrics reveal clear trade-offs between each approach

**Example Outputs:**

| EWMA Anomaly Detection | Metrics Comparison |
|---|---|
| ![](https://github.com/BusraCevik/numpy-microsoft-stock-anomaly-detection/blob/main/outputs/plots/ewma.png) | ![](https://github.com/BusraCevik/numpy-microsoft-stock-anomaly-detection/blob/main/outputs/plots/metrics_comparison.png) |

🔗 [View Repository](https://github.com/BusraCevik/numpy-microsoft-stock-anomaly-detection) · 🔴 [Live Dashboard](https://busracevik.github.io/numpy-microsoft-stock-anomaly-detection/index.html)

---

#### 6. NumPy — Student Score Analysis
> *Demographic & behavioral factors in academic performance*

**Overview:** Analyzes student exam performance using demographic and behavioral data to understand which factors influence academic outcomes.

**Key Concepts:**
- Exploratory data analysis (EDA) on student data
- Score distribution analysis (Math, Reading, Writing)
- Gender-based performance comparison
- First-child status and parent marital status impact analysis
- Identifying weak vs strong relationships in data

**Key Insights:**
- 👩 Reading & writing scores are generally higher for female students; math is slightly higher for males
- 📊 Score distributions follow a near-normal pattern — a stable, clean dataset
- ❌ First-child status and parent marital status have minimal impact on overall performance

**Example Outputs:**

| First Child Analysis | Gender Analysis |
|---|---|
| ![](https://github.com/BusraCevik/numpy-students-score-analysis/blob/main/outputs/first_child_analysis/first_child_gender_analysis.png) | ![](https://github.com/BusraCevik/numpy-students-score-analysis/blob/main/outputs/gender_analysis/gender_mean_scores.png) |

🔗 [View Repository](https://github.com/BusraCevik/numpy-students-score-analysis) · 🔴 [Live Dashboard](https://busracevik.github.io/numpy-students-score-analysis/index.html)

---

### 🟢 Pandas — Data Analysis

---

#### 7. Pandas Basics
> *Building a strong foundation in structured data manipulation*

**Overview:** Covers essential Pandas operations for working efficiently with structured data.

**Key Concepts:**
- DataFrame creation and manipulation
- Indexing, slicing, and filtering data
- GroupBy operations for data aggregation
- Merging and joining multiple datasets
- Handling missing values

🔗 [View Repository](https://github.com/BusraCevik/pandas-basics)

---

#### 8. Pandas — Global Economic Indicators Analysis
> *GDP growth, inflation trends & economic cycles*

**Overview:** Analyzes global economic indicators using Pandas to understand how economies evolve over time, comparing countries and examining economic stability.

**Key Concepts:**
- Time series analysis of economic indicators
- GDP growth rate and economic trend analysis
- Inflation dynamics and trend comparison
- Rolling averages for trend smoothing
- Economic stability analysis using crisis detection
- Visual storytelling with analytical plots

**Key Insights:**
- 📉 Clear economic cycles with global downturns around 2015 and 2020, followed by recovery
- 🔥 Inflation surged strongly after 2020, reflecting a global shift rather than isolated cases
- 🇹🇷 Turkey shows GDP recovery but a sharp inflation rise — indicating increased instability
- 🌍 Crisis year analysis highlights significant differences in economic resilience across countries

**Example Outputs:**

| Countries With the Most Crisis Years | Global GDP Growth Trend |
|---|---|
| ![](https://github.com/BusraCevik/pandas-global-economic-indicators-analysis/blob/main/outputs/png/crisis_years_by_country.png) | ![](https://github.com/BusraCevik/pandas-global-economic-indicators-analysis/blob/main/outputs/png/global_gdp_growth_trend.png) |


🔗 [View Repository](https://github.com/BusraCevik/pandas-global-economic-indicators-analysis) · 🔴 [Live Dashboard](https://busracevik.github.io/pandas-global-economic-indicators-analysis/index.html)

---

#### 9. Pandas — Customer Churn Analysis
> *Understanding why customers leave — and how to stop them*

**Overview:** Analyzes customer churn behavior to understand which segments are most likely to leave a subscription-based service, focusing on contract types, payment methods, tenure, and service usage.

**Key Concepts:**
- Customer segmentation and churn analysis
- Churn rate comparison across categories
- Feature engineering (tenure groups, service flags)
- Behavioral pattern analysis
- Business-oriented data interpretation

**Key Insights:**
- ⚠️ Month-to-month contract customers have ~43% churn rate; two-year contracts drop to ~3%
- 💳 Electronic check users show the highest churn (~45%)
- 🆕 New customers (0–12 months) churn at ~48%; long-term customers are far more stable (~9%)
- 📦 Customers with multiple services have ~32% churn vs ~10% for those with fewer services

**Example Outputs:**

| Churn by Contract | Global GDP Growth Trend |
|---|---|
| ![](https://github.com/BusraCevik/pandas-customer-churn-analysis/blob/main/outputs/figures/churn_by_contract.png) | ![](https://github.com/BusraCevik/pandas-global-economic-indicators-analysis/blob/main/outputs/png/global_gdp_growth_trend.png) |

🔗 [View Repository](https://github.com/BusraCevik/pandas-customer-churn-analysis) · 🔴 [Live Dashboard](https://busracevik.github.io/pandas-customer-churn-analysis/index.html)

---

#### 10. Pandas — Medical Appointment No-Show Analysis
> *Why do patients miss appointments — and what can we do about it?*

**Overview:** Analyzes patient appointment behavior to identify which factors are associated with missed medical visits.

**Key Concepts:**
- No-show rate analysis
- Patient segmentation
- Time-based feature engineering
- Waiting time impact analysis
- Behavioral pattern detection

**Key Insights:**
- 🏥 Overall no-show rate is ~20% — a significant operational challenge
- 👶 Teens have the highest no-show rate (~26%); seniors are the most consistent (~16%)
- ⏳ No-show rates jump from ~6% (0–1 days wait) to ~32% (7+ days wait)
- 📱 SMS reminders correlate with *higher* no-show rates (~28% vs ~17%), suggesting reminders reach already high-risk groups

**Example Outputs:**

| No-Show by Age Group | No-Show by Waiting Days |
|---|---|
| ![](https://github.com/BusraCevik/pandas-medical-appointment-noshow-analysis/blob/main/outputs/figures/noshow_by_age_group.png) | ![](https://github.com/BusraCevik/pandas-medical-appointment-noshow-analysis/blob/main/outputs/figures/noshow_by_waitingdays.png) |

🔗 [View Repository](https://github.com/BusraCevik/pandas-medical-appointment-noshow-analysis) · 🔴 [Live Dashboard](https://busracevik.github.io/pandas-medical-appointment-noshow-analysis/index.html)

---

#### 11. Pandas — E-Commerce RFM & Cohort Analysis
> *Customer segmentation, retention, and revenue dynamics*

**Overview:** Analyzes e-commerce customer behavior using RFM segmentation, cohort retention tracking, and revenue dynamics to uncover actionable business insights.

**Key Concepts:**
- RFM (Recency, Frequency, Monetary) segmentation
- Customer lifetime value analysis
- Cohort analysis and retention tracking
- Time series analysis of revenue and orders
- Revenue contribution by segment

**Key Insights:**
- 💰 Revenue is largely driven by loyal, high-value customers; many users remain low-frequency buyers
- 📉 Clear drop in retention after the first months — churn happens early in the lifecycle
- 📅 Monthly trends show growth followed by fluctuations, suggesting seasonality rather than stable growth
- 🎯 Improving early retention and converting occasional buyers into repeat customers would have the biggest revenue impact

| Customer Retention Cohort Heatmap | Monthly Order Trend |
|---|---|
| ![](https://github.com/BusraCevik/pandas-ecommerce-rfm-cohort-analysis/blob/main/outputs/figures/cohort_retention_heatmap.png) | ![](https://github.com/BusraCevik/pandas-ecommerce-rfm-cohort-analysis/blob/main/outputs/figures/monthly_order_trend.png) |

🔗 [View Repository](https://github.com/BusraCevik/pandas-ecommerce-rfm-cohort-analysis) · 🔴 [Live Dashboard](https://busracevik.github.io/pandas-ecommerce-rfm-cohort-analysis/index.html)

---

#### 12. Pandas — Manufacturing Downtime Analytics
> *Production efficiency, bottleneck detection & throughput analysis*

**Overview:** Analyzes manufacturing operations to understand downtime behavior, production efficiency, and throughput dynamics across multiple time resolutions.

**Key Concepts:**
- Event-level vs hourly reconciliation analysis
- Downtime duration and distribution analysis
- Throughput vs downtime relationship
- Hourly and daily efficiency trends
- Operational stability and variability
- Data consistency and validation

**Key Insights:**
- 🕛 Downtime is not random — it peaks around midday hours, indicating recurring operational bottlenecks
- 📉 Clear negative correlation: higher downtime → lower throughput
- 🔁 Efficiency trends fluctuate significantly, reflecting unstable performance with frequent interruptions
- 🛠️ Targeting specific time windows of instability would significantly improve production performance

| Consistency Validation | Downtime Event Distribution |
|---|---|
| ![](https://github.com/BusraCevik/pandas-manufacturing-downtime-analytics/blob/main/outputs/figures/consistency_validation.png) | ![](https://github.com/BusraCevik/pandas-manufacturing-downtime-analytics/blob/main/outputs/figures/downtime_event_distribution.png) |

🔗 [View Repository](https://github.com/BusraCevik/pandas-manufacturing-downtime-analytics) · 🔴 [Live Dashboard](https://busracevik.github.io/pandas-manufacturing-downtime-analytics/index.html)

---

## 🎓 Education

| Degree | Institution | Period |
|---|---|---|
| M.Sc. Artificial Intelligence & Data Science | Politechnika Częstochowska, Poland | 02.2026 – 09.2027 |
| Erasmus Exchange | Politechnika Częstochowska, Poland | 02.2023 – 06.2023 |
| B.Sc. Software Engineering | Fırat University, Turkey | 08.2020 – 02.2025 |

---

## 💼 Experience

| Role | Company | Period |
|---|---|---|
| Software Engineer Intern | Information Technology Dept., Fırat University | Sep 2024 – Oct 2024 |
| Software Engineer Intern | B&B Bilişim, Kayseri, Turkey | Sep 2022 – Oct 2022 |
| Front-End Developer | Callisto, İstanbul, Turkey | May 2021 – Jul 2022 |

---

## 🌍 Languages

| Language | Level |
|---|---|
| Turkish | Native |
| English | C1 (IELTS) |
| Polish | Beginner (A1) |
| Spanish | Basic (A2) |

---

## 🔮 What's Next

Following a structured roadmap, the next phases of this portfolio will include:

- 🤖 **Machine Learning** — supervised & unsupervised learning, model evaluation
- 🧠 **Deep Learning** — neural networks, CNNs, RNNs
- 🔬 **Thesis Project** — predictive modeling of aircraft engine degradation using ML + XAI (NASA datasets)

---

<div align="center">

*"From fundamentals to AI and Data Science — one project at a time."*

**Let's work together!**
[busrazcvik@outlook.com](mailto:busrazcvik@outlook.com)

</div>
