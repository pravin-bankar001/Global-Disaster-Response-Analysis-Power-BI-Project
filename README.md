# 🌍 Global Disaster Response Analysis | Power BI Dashboard

An interactive **Power BI** project that analyzes global disaster data (2018–2024) to understand disaster frequency, economic loss, casualties, aid distribution, response performance, and recovery trends across countries and disaster types.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Dashboard Pages](#-dashboard-pages)
- [Key KPIs](#-key-kpis)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [Author](#-author)

---

## 📖 Project Overview

This project provides a complete view of global disaster management through a 5-page interactive Power BI report. It helps decision-makers track the scale of disasters, evaluate how efficiently aid is allocated, measure response and recovery performance, and look ahead using forecasting.

## 🎯 Business Problem

Governments and relief organizations need to answer questions such as:
- How many disasters occur each year, and where?
- Which countries and disaster types cause the most economic loss and casualties?
- How is aid distributed across countries and disaster types?
- How fast do teams respond, and does faster response shorten recovery?
- What does the future trend of disaster occurrences look like?

## 🗂 Dataset

| Item | Details |
|------|---------|
| Records | ~50,000 disaster events |
| Period | 2018 – 2024 |
| Source | *Add your dataset source / link here (e.g., Kaggle)* |
| Format | Excel / CSV |

**Key fields:** `country`, `disaster_type`, `year`, `casualties`, `economic_loss_usd`, `aid_amount`, `response_time_hours`, `recovery_duration_days`, `efficiency_score`, `response_time_improvement_%`

> Update the field names above to match your actual dataset.

## 🛠 Tools & Technologies

- **Power BI Desktop** – data modeling, DAX, visualization
- **Power Query** – data cleaning and transformation
- **DAX** – KPI measures and calculations
- **Excel** – raw data source
- **Python visual** *(if used)* – response time variability by disaster type

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview
A high-level summary of global disaster impact with slicers for **Country**, **Disaster Type**, and **Year**.

- KPI cards: Total Disasters, Total Economic Loss, Total Casualties, Total Aid, Average Efficiency, Avg Response Time
- Line chart: Total Disasters by Year
- Map: Country-wise Economic Loss
- Bar chart: Economic Loss by Country

![Executive Overview](images/Executive-Overview.jpg)

---

### 2️⃣ Regional & Country Analysis
Drill into geographic and disaster-type patterns.

- Map: Total Casualties by Country
- Bar chart: Total Economic Loss by Disaster Type
- Matrix with conditional formatting: Casualties and Economic Loss by Disaster Type and Year

![Regional and Country Analysis](images/Regional-Country-Analysis.jpg)

---

### 3️⃣ Aid & Funding
Shows how financial aid is distributed.

- KPI cards: Total Aid, Aid per Casualty
- Waterfall chart: Year-wise Aid Distribution by Disaster Type
- Treemap: Total Aid by Country
- Map: Aid per Affected Person by Country

![Aid and Funding](images/Aid-_-Funding.jpg)

---

### 4️⃣ Response Performance
Evaluates how quickly and efficiently teams respond.

- KPI cards: Average Response Time, Median Response Time, Responses with SLA, % Within SLA
- Scatter plot: Response Time vs Recovery Duration
- Box plot: Response Time Variability by Disaster Type
- Combo chart: Operational Efficiency vs Aid Allocation Timeline

![Response Performance](images/Response-Performance.jpg)

---

### 5️⃣ Recovery & Forecasting
Looks at recovery duration and future trends.

- KPI cards: Average Recovery Duration, Aid per Casualty
- Decomposition tree: Avg Recovery Duration by Country → Disaster Type
- Forecast line chart: Disaster occurrences projected to 2026
- Slicer: Response Time Improvement %

![Recovery and Forecasting](images/Recovery-_-Forecasting.jpg)

---

## 📈 Key KPIs

| KPI | Value |
|-----|-------|
| Total Disasters | **50K** |
| Total Casualties | **5M** |
| Total Economic Loss | **$253.43bn** |
| Total Aid | **$12.50bn** |
| Aid per Casualty | **$2.49K** |
| Average Efficiency | **87.57** |
| Average Response Time | **12.18 hrs** |
| Median Response Time | **10.51 hrs** |
| Responses Within SLA | **100%** |
| Average Recovery Duration | **49.68 days** |

## 💡 Key Insights

- **Disaster frequency peaked in 2021** (~7,270 events) and has declined since, reaching about 7,085 in 2024.
- **Forecast shows a largely flat trend** for disaster occurrences through 2026.
- **Economic loss is spread evenly** across disaster types, with Volcanic Eruption, Landslide, and Earthquake slightly highest.
- **Brazil, Bangladesh, and China** are among the countries with the highest economic loss.
- **Aid is relatively stable year to year** (~$1.8bn annually), while efficiency fluctuates only slightly (87.5–87.7).
- **Faster response is loosely linked to longer recovery in some clusters**, suggesting response speed alone doesn't determine recovery time.
- **Average recovery duration is ~50 days** across countries, with little variation by country and disaster type.

> Review and edit these insights so they match what you observe in your final report.

## ✅ Recommendations

1. Prioritize aid toward countries with high economic loss and low aid per affected person.
2. Invest in response-time improvement, since efficiency scores still have room to grow.
3. Monitor disaster types with long recovery durations (e.g., Storm Surge, Flood) for targeted preparedness.
4. Keep tracking SLA compliance together with recovery outcomes, not response time alone.

## 👤 Author

**Pravin Bankar**
- LinkedIn: [your-link](linkedin.com/in/pravin-bankar)
