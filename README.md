# 🇯🇵 **Japan Tourism Data Analysis (1970–2024)**

**Business Analysis • Data Visualization • Tableau • Exploratory Insights**

This project provides a comprehensive analysis of Japan’s inbound tourism using long-term historical trends (1964–2024) and detailed 2024 segmentation data. It is designed to give stakeholders a **clear, business-ready view** of Japan’s tourism performance, visitor behavior, and market opportunities.

The analysis includes:

* Historical visitor growth (1964–2024)
* 2024 visitor segmentation by nationality, region visited, purpose of visit, and demographics
* Regional concentration analysis
* Spending distribution and high-value segments
* Year-over-year growth patterns

The dashboards and insights are crafted for **executives, tourism agencies, and business teams** seeking actionable findings.

---

## **Dashboards**

### **1. Japan Visitor Trends (1964–2024)**

* Historical inbound arrivals
* YoY growth rate
* Country-level trend comparison

### **2. Japan Tourism Segmentation (2024)**

* Regions visited (prefecture-level)
* Visitor nationality
* Purpose of visit
* Age & gender segmentation

> Final dashboard images and **TWBX file** are available in `/dashboard/`.

---

## **Data Sources**

| Dataset          | Year      | Description                       | File                                        |
| ---------------- | --------- | --------------------------------- | ------------------------------------------- |
| Visitor Arrivals | 1964–2024 | Total inbound visitors            | `japan_visitors_amount_1964_2025_clean.csv` |
| Country Arrivals | 2024      | Arrivals by nationality           | `japan_visitors_nationality_2024_clean.csv` |
| Regions Visited  | 2024      | Prefecture/region visitation      | `japan_region_visit_2024_clean.csv`         |
| Purpose of Visit | 2024      | Tourism, business, study, medical | `japan_visitors_purpose_2024_clean.csv`     |
| Age Distribution | 2024      | Visitors by age                   | `japan_visitors_age_2024_clean.csv`         |

**Official Sources:**

* JNTO – Japan National Tourism Organization
* JTA – Japan Tourism Agency

All datasets are located in `/02_data/`.

---

## **Data Cleaning & Transformation (Power Query)**

Processing was performed using **Microsoft Power Query (M Language)** to standardize all datasets into a clean analytical model.

Key steps included:

### **Unpivoting**

Converted multi-column wide tables into long format for Tableau compatibility.

### **Standardization**

* Normalized country/region names
* Unified date formats (YYYY or MMM YYYY)

### **Type Conversion**

* Converted visitor counts to integers
* Ensured spending/percentage fields used numeric formats

### **Deduplication & Validation**

* Removed duplicates
* Verified totals between regional and national datasets

The result is a clean, analysis-ready dataset for BI use.

---

## **Analytical Framework**

### **1. KPI Definition**

* Total inbound visitors (1964–2024)
* YoY growth rate
* Top markets (2024)
* Regional visitation share
* Spending share by purpose

### **2. Data Processing**

* Cleaned and merged raw CSVs
* Calculated YoY growth & market shares
* Built segmentations by nationality, purpose, age group

### **3. Visualization in Tableau**

* KPI tiles
* Historical line trends
* Regional filled map
* Top country bar charts
* Purpose and demographic breakdowns

---

## **Scope Definition**

### **Included (In-Scope)**

✔ Historical visitor analysis (1964–2024)

✔ Economic insights (spending share by nationality & purpose)

✔ Detailed segmentation (purpose, demographics, nationality)

✔ Core tourism KPIs

✔ Regional distribution analysis

### **Out-of-Scope**

❌ Forecasting or predictive modeling

❌ Projections beyond 2024

❌ Primary data collection (surveys/interviews)


---

## **Key Insights**

### **1. Tourism Recovery & Growth**

Japan’s inbound tourism reached **record levels in 2024**, continuing a long-term upward trend driven by mobility improvements and visa liberalization.

**Implication:** Japan remains a strong, high-demand tourism destination.


### **2. Market Concentration: Top Nationalities**

A small group of countries—**South Korea, China, Taiwan**—contribute the majority of arrivals.

**Implication:** Japan is exposed to risks from geopolitical or economic shifts; market diversification is recommended.


### **3. Regional Distribution Imbalance**

Visitor activity is heavily concentrated in **Kanto (51.49%)** and **Kansai (39.57%)**.

**Implication:** Secondary regions offer high-growth potential with targeted campaigns.


### **4. Demographic Profile**

The core visitor group is **30–39 years old (41.13%)**, with a slight male majority (54.15%).

**Implication:** Marketing should focus on digital-first experiences tailored to working professionals and young families.


### **5. High-Value Niche Segments**

Study, medical, and training visitors represent **<2% of total arrivals**, but account for **36%+ of total spending**.

**Implication:** Sustainable revenue growth lies in developing high-value niche markets—not only in driving mass tourism.

---

## **Deliverables**

* Tableau Dashboard (`.twbx` + PNG exports)
* Clean datasets
* Project brief
* Data dictionary
* Presentation slides

All deliverables are neatly organized in labeled folders.

---

## **Tools & Technologies**

* **Tableau Public** — dashboarding
* **Excel / Power Query** — cleaning & transformation
* **Notion** — documentation
* **PowerPoint** — insight storytelling

---

## **About the Analyst**

Hi, I’m **Syahraini**, transitioning into Business Analysis from an accounting background. I specialize in building **clear, executive-ready dashboards** and turning complex datasets into practical insights.

---

## **Contact**

* **LinkedIn:** [https://linkedin.com/in/nsyahraini](https://linkedin.com/in/nsyahraini)
* **Portfolio:** [https://bit.ly/syahrainiportfolio](https://bit.ly/syahrainiportfolio)
* **Email:** [syahraini.nur@outlook.com](mailto:syahraini.nur@outlook.com)

---
