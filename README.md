**🇯🇵 Japan Tourism Data Analysis (1970–2024)**

Business Analysis • Data Visualization • Tableau • Exploratory Insights

This project analyzes Japan’s tourism performance using:
- Long-term visitor trends (1964–2024)
- 2024 segmentation data (nationality, region visited, purpose of visit, demographics)
- Regional distribution of visitor activity
- Year-over-year growth patterns

The goal is to produce a clear, business-ready overview of Japan’s tourism recovery, market drivers, and key visitor characteristics.

---

## 📊 Dashboards

### **1. Japan Visitor Trends (1964–2024)**
- Historical arrivals  
- YoY growth  
- Country-level trends  

### **2. Japan Tourism Segmentation (2024)**
- Region visited (prefecture-level)  
- Visitor nationality  
- Purpose of visit  
- Demographics  

📌 *Final dashboard image and TWBX file included in `/dashboard/`.*

---

## 🔍 Data Sources

| Dataset | Year | Description | File |
|--------|------|-------------|-------|
| Visitor arrivals | 1964–2024 | Total inbound visitors | `japan_visitors_amount_1964_2025_clean` |
| Country arrivals | 2024 | Visitors by nationality | `japan_visitors_nationality_2024_clean` |
| Regions visited | 2024 | Prefecture/region visitation | `japan_region_visit_2024_clean` |
| Purpose of visit | 2024 | Tourism/business/others | `japan_visitors_purpose_2024_clean` |
| Age distribution | 2024 | Visitors by age | `japan_visitors_age_2024_clean` |

**Original sources:** 
- JNTO (Japan National Tourism Organization)  | https://statistics.jnto.go.jp/en/graph/
- JTA (Japan Tourism Agency) | https://www.mlit.go.jp/kankocho/en/siryou/toukei/syouhityousa.html
*All files are stored in `/data/raw/`.*

---

## 🧪 Data Quality & Cleaning Summary

Key cleaning steps:
- Standardized date formats (YYYY or MMM YYYY)
- Normalized country and region names
- Converted visitor counts to integers
- Corrected rate columns to decimals
- Removed duplicated rows
- Checked that regional sums align with national totals (within data limits)
  
---

## 📈 Analytical Approach

**1. KPI Definition**
- Total inbound visitors (1970–2024)
- YoY growth rate
- Top visitor markets (2024)
- Region visitation distribution (2024)

**2. Data Processing**
- Cleaned raw CSVs
- Joined datasets where needed
- Calculated YoY, growth percentages, and share of visitors
- Built regional and purpose-based segmentations

**3. Visualization (Tableau)**
- KPI tiles  
- Line chart (1970–2024 trends)  
- Bar chart (top countries)  
- Filled map (regions visited)  
- Segmentation breakdown  

---

## 💡 Key Insights (High-level)

- **2024 hit an all-time record** for inbound visitors  
- Strong recovery driven by **South Korea, China, Taiwan**  
- **Kanto and Kansai** remain the most visited regions  
- Visitors primarily come for **tourism and leisure**, followed by business  
- Age distribution shows strong presence of **20–39** traveler segment  

(*Detailed insights available in the presentation slides.*)

---

## 🗂️ Deliverables

- ✔ Tableau dashboard (`.twbx`, PNG)  
- ✔ Clean datasets  
- ✔ Project brief  
- ✔ Data dictionary  
- ✔ Slide presentation  

All files are available in the respective folders.

---

## 🧭 How to Reproduce

1. Download the repository  
2. Open the `.twbx` Tableau file  
3. Ensure all CSVs remain in the same relative folder paths  
4. Explore/modify the dashboards  

---

## 👩‍💻 Tools Used
- **Tableau Public** — visualizations  
- **Excel** — data cleaning  
- **Notion** — brief and planning  
- **Power Point** — insights presentation  

---

## 🙋‍♀️ About the Analyst

Hi, I’m **Syahraini**, transitioning into Business Analysis with a background in accounting.  
I focus on clean, stakeholder-ready dashboards and practical insights driven by real-world data.

---

## 📬 Contact

- **LinkedIn:** *www.linkedin.com/in/nsyahraini*  
- **Portfolio:** *https://bit.ly/syahrainiportfolio*  
- **Email:** *syahraini.nur@outlook.com*  

---
