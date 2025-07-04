# 🦠 COVID-19 Analysis: Cases, Deaths, and Global Trends

### 👨‍💻 Developer: Aaryan M

This project offers a comprehensive analysis of the global impact of the COVID-19 pandemic. It uses real-world datasets and combines the power of **Python** for data wrangling and **Power BI** for interactive dashboard visualizations. The primary objective is to uncover patterns, evaluate response strategies, and understand how the virus spread and affected different regions globally.

---

## 📌 Project Overview

The dataset is transformed to focus on daily confirmed cases by **melting date columns into rows**, allowing for **time-series analysis**. The data is cleaned, standardized, and visualized to extract meaningful insights about the pandemic's trajectory.

---

## 🎯 Goals & Objectives

- Analyze confirmed cases and death rates across different countries.
- Identify the top 10 most affected nations by total cases and deaths.
- Determine how quickly countries reached critical infection milestones (e.g., 1,000 cases).
- Study death distribution across continents.
- Rank nations based on weekly growth rates of infection.

---

## 📊 Key Analyses Performed

- ✅ Top 10 countries by confirmed cases and deaths  
- ✅ Countries with the slowest spread to 1,000 cases  
- ✅ Monthly trend of confirmed cases by country  
- ✅ Continent-wise COVID-19 death distribution  
- ✅ Top 10 countries by highest weekly growth rate

---

## 🛠️ Tools & Technologies Used

| Tool/Library      | Purpose                                   |
|------------------|--------------------------------------------|
| **Python**       | Data preparation & transformation          |
| **Pandas**       | Data cleaning, reshaping, and aggregation  |
| **Seaborn**      | Advanced visualizations                    |
| **Matplotlib**   | Plotting and visual exploration            |
| **Power BI**     | Dashboard creation & data modeling         |
| **Power Query**  | Data transformation within Power BI        |

---

## 🔄 Process Methodology

### 1. Data Collection
- Sourced confirmed case and happiness index data from reliable sources.

### 2. Data Preparation
- Cleaned missing values, unified date formats, renamed columns.
- Normalized country names for consistency.

### 3. Data Transformation
- Melted date columns into rows to create a proper time series format.
- Converted strings to `datetime` format and sorted records.
- Grouped data by country and time for cumulative trend analysis.

### 4. Data Analysis & Visualization
- Created various visualizations using `matplotlib` and `seaborn`.
- Published an interactive dashboard using **Power BI** with:
  - Bar charts, line charts, pie charts
  - DAX-calculated fields
  - Country-level drilldowns

### 5. Insights & Interpretation
- Uncovered insights on spread velocity, mortality clusters, and growth trends.

### 6. Conclusion & Documentation
- Compiled all findings, charts, and techniques into a presentation-ready format.

---


---

🔮 Future Improvements
Add recovery and vaccination metrics

Automate data refresh via Power BI Service

Deploy dashboard to Power BI web for public access

Integrate mobility and policy data for deeper correlation




