# Nutrition, Physical Activity, and Obesity – BRFSS (2011–2023)

## 📌 Project Overview
This project analyzes data from the **Behavioral Risk Factor Surveillance System (BRFSS)**, a health-related survey conducted annually by the CDC.  
The dataset spans **2011–2023** and focuses on:
- Obesity and weight status
- Physical activity behaviors
- Demographic and socioeconomic stratifications
- Geographic variations across U.S. states

The goal is to identify **trends, disparities, and correlations** that inform public health interventions and policy development.

---

## 📊 Dataset Details
- **Source:** CDC BRFSS (2011–2023)  
- **Population:** Adults aged 18+ across U.S. states  
- **Key Variables:**
  - **Obesity/Weight Status (Q036, Q037)** – BMI-based classification
  - **Physical Activity (Q044–Q047)** – adherence to aerobic & muscle-strengthening guidelines
  - **Demographics:** Age, sex, race/ethnicity, education, income
  - **Geographic:** State-level data with coordinates
  - **Statistical Metrics:** Confidence intervals, sample sizes, footnotes

---

## ⚙️ Data Preprocessing
Steps applied to ensure clean and reliable analysis:
- **Data Cleaning:** Handling missing values, duplicates, and outliers
- **Integration:** Combining annual/state datasets into unified structure
- **Transformation:** Normalization, aggregation, categorical encoding
- **Reduction:** Selecting relevant variables, removing redundancies
- **Validation:** Ensuring logical ranges (e.g., obesity % between 0–100)

---

## 📈 Analysis Objectives & Outcomes

### 1. Obesity Trends (2011–2023)
- **Finding:** Obesity increased from **31.34% (2011)** to **33.58% (2023)** (+2.24%).  
- **Notable Spike:** 2019–2020, possibly linked to COVID-19.

### 2. Physical Activity Trends
- **Finding:** Decline from **32.47% (2012)** to **29.71% (2023)** (−2.76%).  
- Suggests inverse relationship with obesity.

### 3. State Comparisons
- **Highest Obesity:** Mississippi (35.46%), West Virginia (35.98%)  
- **Lowest Obesity:** Colorado (23.19%)  
- Regional disparities: Southeast vs. West.

### 4. Correlation Analysis
- Weak negative correlation between physical activity & obesity (R² ≈ 0.03).  
- Outlier: Colorado (low obesity, high activity).

### 5. Sex-Based Trends
- Females consistently higher obesity rates than males.  
- Male obesity rose sharply from **30.27% (2011)** to **40% (2023)**.

### 6. Race/Ethnicity Disparities
- Radar chart shows dietary differences.  
- **Highest fruit/veg consumption:** American Indian/Alaska Native (3081.5%).  
- **Lowest:** Non-Hispanic White (2611.2%).

### 7. Income-Level Insights
- Lower-income groups (<$15,000) show higher obesity prevalence.  
- Higher-income groups (> $75,000) show lower rates.

---

## 🗺️ Visualizations
- Line graphs: Obesity & Physical Activity trends
- Bar charts: State comparisons, sex-based obesity
- Scatter plots: Correlation between activity & obesity
- Choropleth maps: Obesity rates by state
- Pie charts: Year-wise obesity distribution
- Radar charts: Race/ethnicity dietary disparities
- Slicer dashboards: Interactive filtering by income, age, sex

---

## 🎯 Real-World Applications
- **Public Health Interventions:** Target high-obesity states (e.g., Mississippi, Alabama).  
- **Policy Development:** Allocate resources to Southeast regions.  
- **Healthcare Planning:** Prepare for chronic disease management in high-risk states.  
- **Community Planning:** Promote walkable cities, affordable gyms, and nutrition centers.

---

## 📂 Repository Structure
