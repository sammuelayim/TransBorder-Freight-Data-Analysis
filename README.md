# 🚚 Transborder Freight Data Analysis  
**Leveraging CRISP-DM to Optimize North America's Freight Efficiency**  
[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/sammuelayim/TransBorder-Freight-Data-Analysis)  

## 📌 Overview
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
Validate findings through cross-referencing benchmarks and stakeholder feedback to ensure actionable insights

---


---

## 🔍 Key Research Questions & Findings  
**Below are the core questions explored, aligned with the analysis sections (A-H) in the report:**  

### **A) How do freight movement patterns vary across transportation modes over time?**  
📈 **Visualization:** [Freight Volume Trends by Mode]![image](https://github.com/user-attachments/assets/b61aa109-1e8e-4f37-ba8c-2d1ae34401a6)

  
**Key Findings:**  
- **Road transport dominates (65% share)**, but rail and pipeline usage declined post-2022.  
- **Air and Foreign Trade Zones (FTZs)** grew steadily for high-value, low-weight shipments.  
- **Post-pandemic recovery (2021–2022)** boosted freight, but 2024 saw declines due to economic shifts.  

---

### **B) Which regions experience the most congestion?**  
📍 **Visualization:** [Congestion Hotspots]![image](https://github.com/user-attachments/assets/c4be5517-a361-49d0-9096-39e84c2fcc2e)
 
**Key Findings:**  
- **Texas (39XX)**, **California (5301)**, and **Michigan (2304)** are top congested regions.  
- Midwestern/border states face bottlenecks due to high trade activity and infrastructure constraints.  

---

### **C) What is the environmental impact of transportation mode?**  
🌿 **Visualization:** [Emissions by Mode]![image](https://github.com/user-attachments/assets/92b575e0-a16f-4326-9117-320bc3647eee)
 
**Key Findings:**  
- **Air freight emits 3x more CO₂ per ton-mile** than road/rail.  
- Transitioning **10% of road freight to rail** could reduce emissions by **30%**.  

---

### **D) How is DISAGMOT distributed across regions/years?**  
🚛 **Visualization:** [Transport Mode Distribution]![image](https://github.com/user-attachments/assets/e8070e42-c7c4-4ddb-b7ee-9847fe511b94)
  
**Key Findings:**  
- **Trucking (Code 3)** dominates trade value, peaking in 2023.  
- **Pipeline and vessel** handle bulk shipments, with pipeline growth until 2023.  

---

### **E) What is the total shipment value by state/country?**  
💰 **Visualization:** [Shipment Value by State]![image](https://github.com/user-attachments/assets/3ebf2f1c-e22b-467d-9c1a-5a048f7660a4)
  
**Key Findings:**  
- **Texas (\$90B)**, **California (\$75B)**, and **Michigan (\$65B)** lead in shipment value.  
- Coastal states (TX, CA) thrive via ports; industrial states (MI, OH) excel in manufacturing.  

---

### **F) How do freight charges compare for imports vs. exports?**  
📦 **Visualization:** [Freight Charges by Trade Type]![image](https://github.com/user-attachments/assets/998cc8fd-adc0-44d5-837d-d70a10955718)

**Key Findings:**  
- **Import costs exceed exports by 15–20%** due to tariffs and customs delays.  
- Streamlining import logistics could save millions annually.  

---

### **G) What factors drive seasonal freight trends?**  
📅 **Visualization:** [Seasonal Volume Peaks]![Monthly Freight Volume Trends](https://github.com/user-attachments/assets/6f2e3f3b-9c40-4aae-9daa-783607a677e5)
  
**Key Findings:**  
- Peaks in **Q2 (April–June)** and **Q4 (June–August)** align with industrial demand and holidays.  
- January/February saw the lowest activity due to seasonal slowdowns.  

---

### **H) How are transport modes distributed across states?**  
🗺️ **Visualization:** [State-wise Mode Distribution]![Trends in Freight Volume Across Different Transportation Modes Over Time](https://github.com/user-attachments/assets/3cf624f2-dc4d-49ec-b006-2d2572c76440)
  
**Key Findings:**  
- **Texas and California** rely on trucks (Code 3) and rail (Code 5).  
- **Florida/Georgia** use vessels (Code 6) for port access.  

---
 

### **6. Deployment**  
- **Deliverables:** Dashboards, Python scripts, and recommendations.  
  

---

## 💡 Key Insights  
1. **Road transport dominates** but causes 65% of emissions.  
2. **Texas, California, and Michigan** are critical hubs needing infrastructure upgrades.  
3. **Import costs are 20% higher** due to tariffs and bottlenecks.  
4. **Shifting 10% of road freight to rail** could cut emissions by 30%.  

---

## 🚀 Recommendations  
1. **Expand rail/water infrastructure** to reduce road dependency.  
2. **Optimize import logistics** via bulk discounts and automated customs.  
3. **Adopt electric trucks** in congested states like Texas.  
4. **Use predictive analytics** to manage seasonal peaks.  

---

## 🔧 Tools & Technologies  
- **Languages:** Python (Pandas, NumPy)  
- **Libraries:** Scikit-learn, Dask  
- **Visualization:** Tableau, Matplotlib  
- **Version Control:** Git/GitHub  

---

**[Explore the Full Analysis](https://docs.google.com/document/d/1jUGwrrWwQmCcc4NUUxnosqSCrIsB6Ujz/edit)**  
*Dashboards, code, and datasets available in this repository.*  

- **Repo Structure:**
```
├── data/ # Raw & cleaned datasets
├── notebooks/ # Jupyter notebooks
├── scripts/ # Data processing & analysis
├── visualizations report/ # Charts & dashboards
└── README.md # Project overview
