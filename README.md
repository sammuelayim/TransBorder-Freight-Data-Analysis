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
