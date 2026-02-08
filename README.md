# COVID-19 Data Analysis using Exploratory Data Analysis

## Internship Mini Project  
*Organization:* Hex Softwares Pvt. Ltd.  
*Project Type:* Data Science Internship Project  
*Difficulty Level:* Intermediate  
*Target Dataset:* Global COVID-19 Dataset (Johns Hopkins University via Kaggle)  

---

## Project Overview
This project focuses on analyzing global COVID-19 data to understand the spread, impact, and trends of the pandemic across different countries and time periods.  
The objective is to extract meaningful insights related to *confirmed cases, deaths, recoveries, mortality rates, recovery trends, and temporal patterns* using comprehensive exploratory data analysis and visualization techniques.

The project follows an **industry-aligned data analysis pipeline**, covering:
- Data Collection
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Time-Series Analysis
- Visualization & Reporting
- Insight Generation

---

## Data Source & Ethical Compliance
- *Dataset:* COVID-19 Clean Complete Dataset  
- *Source:* Kaggle (Johns Hopkins University COVID-19 Data)  
- *Usage Type:* Educational (Non-commercial)

### Data Privacy & Compliance Measures
- ✔️ Used publicly available global COVID-19 dataset  
- ✔️ No personal or sensitive individual-level data accessed  
- ✔️ Data used strictly for educational and analytical purposes  
- ✔️ Original data sources properly credited  
- ✔️ Analysis conducted in compliance with Hex Softwares internship guidelines  

This ensures adherence to ethical data usage and privacy standards.

---

## Tools & Technologies
- Python 3.8+
- pandas, numpy
- matplotlib, seaborn
- plotly (interactive visualizations)
- folium (geographical analysis)
- Google Colab (Primary Development Environment)
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Collection & Preparation
- Downloaded COVID-19 global dataset from Kaggle
- Loaded and inspected dataset structure
- Verified date ranges, country coverage, and data consistency
- Prepared dataset for preprocessing and analysis

### 2. Data Cleaning & Preprocessing
- Handled missing values in geographical and numerical fields
- Created derived features such as:
  - Active cases
  - Mortality rate
  - Recovery rate
  - Month and year attributes
- Aggregated country-level summaries
- Generated clean, analysis-ready datasets

### 3. Exploratory Data Analysis (EDA)
- Global COVID-19 statistics analysis
- Country-wise comparison of confirmed cases, deaths, and recoveries
- Distribution analysis using histograms and box plots
- Correlation analysis between key variables
- Identification of top affected countries

### 4. Time-Series & Trend Analysis
- Global and country-level time-series analysis
- Daily and monthly growth rate analysis
- 7-day moving average trend smoothing
- COVID-19 wave identification using peak detection techniques

### 5. Data Visualization
- Static visualizations using Matplotlib and Seaborn
- Interactive charts using Plotly
- Choropleth world map for global case distribution
- Scatter plots to analyze relationships between confirmed cases, deaths, and recovery trends

### 6. Insights & Reporting
- Extracted key global and country-level insights
- Identified temporal patterns and wave behavior
- Highlighted correlations and notable trends
- Documented limitations and data biases
- Provided high-level public health and analytical observations

---

## 📊 Key Insights
- COVID-19 spread shows clear **wave-like patterns** over time
- High confirmed case counts do not always correlate with high mortality rates
- Recovery rates vary significantly across countries
- Strong positive correlation between confirmed cases and deaths
- Healthcare capacity and early response appear to influence outcomes more than case volume alone

---

## ⚠️ Limitations
- Data quality varies across countries due to reporting standards
- Testing rates differ significantly by region
- Vaccination data not included in this analysis
- Socio-economic and healthcare infrastructure factors not explicitly modeled
- Dataset may not reflect the most recent variants or policy changes

---

## 👤 Individual Contribution
- **Complete Project:** Md Haris Asad (Solo Project)
- **Data Processing:** Data cleaning, feature engineering, aggregation
- **Analysis & Visualization:** EDA, time-series analysis, plotting
- **Insight Generation:** Interpretation of trends and patterns
- **Documentation:** Full project documentation and reporting

---

## 📝 Compliance Statement
This project strictly follows ethical data analysis practices and Hex Softwares internship guidelines.  
All data used is publicly available and properly attributed. No proprietary, restricted, or private data was accessed.

---

## 📉 Data Limitations & Biases
The dataset represents aggregated global COVID-19 statistics and therefore:
- Reflects country-level reporting accuracy and policies
- May underrepresent actual cases due to testing limitations
- Is subject to temporal and reporting delays
- Does not capture individual-level health or demographic factors

These limitations are clearly acknowledged in the analysis and reporting.

---

**Hex Softwares Pvt. Ltd.**  

*Data Science Internship – Task 3*  

## 📁 Project Structure

```text
HexSoftwares_Covid19_Data_Analysis/
│
├── notebooks/
│   └── HexSoftwares_Covid19_Analysis.ipynb  # Complete Jupyter notebook
│
├── data/
│   ├── covid_19_cleaned.csv
|   ├── covid_country_summary.csv
│
├── requirements/
