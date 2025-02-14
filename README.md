# Trans Border Freight Data Analysis

## Overview
This project utilizes data from the Bureau of Transportation Statistics (BTS) to analyze freight transportation across various modes—road, rail, air, and water. By applying the CRISP-DM framework, our goal is to uncover inefficiencies, evaluate safety and environmental impacts, and propose actionable recommendations for enhancement. The dataset encompasses a comprehensive range of monthly data from 2020 to 2024, providing a robust foundation for meaningful insights and improvements in freight transportation efficiency and sustainability.

## Problem Statement
Freight transportation faces significant challenges, including congestion, safety risks, environmental concerns, and economic disruptions. This project aims to address these issues through data-driven analysis.

## Objectives
1. Analyze freight movement patterns across modes and regions.
2. Identify operational inefficiencies such as congestion and underutilized infrastructure.
3. Assess environmental impacts, including emissions.
4. Provide actionable recommendations for improving safety, efficiency, and sustainability.

## Key Research Questions
1. What are the trends in freight volume across different transportation modes over time?
2. Which regions experience the most congestion or inefficiency?
3. How do environmental metrics, such as emissions, vary by transportation mode?
4. What are the most common safety incidents, and where do they occur?
5. Total Value of Shipments by Country and State
6. Freight Charges by Trade Type
7. Distribution of DISAGMOT Across Different States
8. What is the total shipment value for each TRDTYPE (trade type)?

## CRISP-DM Framework
![image](https://github.com/user-attachments/assets/957c8c94-19e1-445b-a24c-63dacb46669f)

### 1. Business Understanding
Define goals and analytical questions to address BTS’s challenges, focusing on inefficiencies, environmental impacts, and safety concerns.

### 2. Data Understanding
- Review dataset structure and attributes.
- Assess data quality (missing values, anomalies).
- Tools: Pandas Profiling, Tableau Prep.

### 3. Data Preparation
- **Cleaning:** Handle missing values, standardize units, and correct anomalies.
- **Integration:** Merge datasets into a consolidated database.
- **Feature Engineering:** Create metrics like emission estimates and congestion indices.
- Tools: Python (Pandas, NumPy), Dask, PySpark.

### 4. Modeling and Analysis
- **Trend Analysis:** Identify freight trends over time.
- **Geospatial Analysis:** Map freight flows and bottlenecks using GeoPandas.
- **Pattern Recognition:** Use clustering to group regions or commodities.
- **Environmental and Safety Assessment:** Analyze emissions and safety incidents.
- Tools: Matplotlib, Plotly, GeoPandas, Scikit-learn.

### 5. Evaluation
Validate findings through cross-referencing benchmarks and stakeholder feedback to ensure actionable insights.

```markdown
 6. Deployment
Organize results and insights in a GitHub repository:

├── data/
│   ├── raw/          # Raw datasets
│   ├── cleaned/      # Processed datasets
├── notebooks/        # Jupyter notebooks for analysis
├── scripts/          # Python scripts
├── visualizations/   # Charts and dashboards
├── README.md         # Project overview
```

---

## 7. Deliverables
- **Visualization File:** Dashboards summarizing insights.
- **Documentation:** Comprehensive README file.
- **Code File:** Clean, reusable scripts.
- **Presentation File:** Methods, findings, and recommendations summary.

---

## Skills and Tools Needed
### Skills
- Data Engineering
- Data Wrangling
- Visualization
- Documentation

### Tools
- **Programming Languages:** Python (Pandas, NumPy, Matplotlib, GeoPandas)
- **Libraries:** Dask
- **Visualization Tools:** Tableau, Power BI
- **Version Control:** Git/GitHub
```
# 🚚 Transborder Freight Data Analysis  
**Leveraging CRISP-DM to Optimize North America's Freight Efficiency**  
[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/sammuelayim/TransBorder-Freight-Data-Analysis)  

---

## 📌 Overview  
This project analyzes **transborder freight data (2020–2024)** from the Bureau of Transportation Statistics (BTS) to address critical challenges in North America's freight industry: **congestion, rising costs, environmental impact, and inefficiencies**. Using the **CRISP-DM framework**, we uncover actionable insights to optimize transportation modes, reduce emissions, and enhance supply chain sustainability.  

---

## 🔍 Key Research Questions & Findings  
**Below are the core questions explored, aligned with the analysis sections (A-H) in the report:**  

### **A) How do freight movement patterns vary across transportation modes over time?**  
📈 **Visualization:** [Freight Volume Trends by Mode](media/image6.png)  
**Key Findings:**  
- **Road transport dominates (65% share)**, but rail and pipeline usage declined post-2022.  
- **Air and Foreign Trade Zones (FTZs)** grew steadily for high-value, low-weight shipments.  
- **Post-pandemic recovery (2021–2022)** boosted freight, but 2024 saw declines due to economic shifts.  

---

### **B) Which regions experience the most congestion?**  
📍 **Visualization:** [Congestion Hotspots](media/image7.png)  
**Key Findings:**  
- **Texas (39XX)**, **California (5301)**, and **Michigan (2304)** are top congested regions.  
- Midwestern/border states face bottlenecks due to high trade activity and infrastructure constraints.  

---

### **C) What is the environmental impact by transportation mode?**  
🌿 **Visualization:** [Emissions by Mode](media/image4.png)  
**Key Findings:**  
- **Air freight emits 3x more CO₂ per ton-mile** than road/rail.  
- Transitioning **10% of road freight to rail** could reduce emissions by **30%**.  

---

### **D) How is DISAGMOT distributed across regions/years?**  
🚛 **Visualization:** [Transport Mode Distribution](media/image9.png)  
**Key Findings:**  
- **Trucking (Code 3)** dominates trade value, peaking in 2023.  
- **Pipeline and vessel** handle bulk shipments, with pipeline growth until 2023.  

---

### **E) What is the total shipment value by state/country?**  
💰 **Visualization:** [Shipment Value by State](media/image11.png)  
**Key Findings:**  
- **Texas (\$90B)**, **California (\$75B)**, and **Michigan (\$65B)** lead in shipment value.  
- Coastal states (TX, CA) thrive via ports; industrial states (MI, OH) excel in manufacturing.  

---

### **F) How do freight charges compare for imports vs. exports?**  
📦 **Visualization:** [Freight Charges by Trade Type](media/image12.png)  
**Key Findings:**  
- **Import costs exceed exports by 15–20%** due to tariffs and customs delays.  
- Streamlining import logistics could save millions annually.  

---

### **G) What factors drive seasonal freight trends?**  
📅 **Visualization:** [Seasonal Volume Peaks](media/image5.png)  
**Key Findings:**  
- Peaks in **Q2 (April–June)** and **Q4 (June–August)** align with industrial demand and holidays.  
- January/February saw the lowest activity due to seasonal slowdowns.  

---

### **H) How are transport modes distributed across states?**  
🗺️ **Visualization:** [State-wise Mode Distribution](media/image13.png)  
**Key Findings:**  
- **Texas and California** rely on trucks (Code 3) and rail (Code 5).  
- **Florida/Georgia** use vessels (Code 6) for port access.  

---

## 🛠️ CRISP-DM Framework Walkthrough  
### **1. Business Understanding**  
- **Goal:** Optimize freight efficiency, reduce costs, and improve sustainability.  
- **Key Questions:** Congestion hotspots, emission disparities, import/export cost gaps.  

### **2. Data Understanding**  
- **Data Source:** BTS Transborder Raw Data (2020–2024).  
- **Tools:** Pandas Profiling, Tableau Prep for quality assessment.  

### **3. Data Preparation**  
- **Cleaning:** Handled missing values, and standardized units.  
- **Feature Engineering:** Created emission estimates and congestion indices.  
- **Tools:** Python (Pandas, Dask), PySpark.  

### **4. Modeling & Analysis**  
- **Trend Analysis:** Identified declining rail usage post-2022.  
- **Geospatial Mapping:** Highlighted Texas and California as congestion hubs.  
- **Tools:** GeoPandas, Matplotlib, Scikit-learn.  

### **5. Evaluation**  
- Validated findings against industry benchmarks (e.g., emission factors).  

### **6. Deployment**  
- **Deliverables:** Dashboards, Python scripts, and recommendations.  
- **Repo Structure:**  

