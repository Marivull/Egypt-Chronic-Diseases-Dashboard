# Egypt-Chronic-Diseases-Dashboard
Comprehensive Power BI dashboard analyzing chronic diseases in Egypt with 118M+ population data covering 33 diseases, risk factors, and economic burden


---

## 🎯 Project Overview

This interactive Power BI dashboard provides in-depth analysis of chronic non-communicable diseases (NCDs) in Egypt, covering:

- **33 Chronic Diseases** across 9 categories
- **14 Risk Factors** affecting 118.4M population
- **372.6B EGP** annual economic burden (89% of healthcare budget)
- **645K Annual Deaths** from NCDs (81% of all deaths)
- **20 Governorates** geographic distribution analysis

---

## 📸 Dashboard Pages

### Page 1: Executive Overview


### Page 2: Disease Categories


### Page 3: Disease-Level Insights


### Page 4: Risk Factors & Comorbidities


---

## 📊 Key Findings

### Disease Prevalence
- **71% of Egyptians** (84.1M people) affected by at least one chronic disease
- **Top 3 Diseases:**
  1. Cardiovascular Diseases - 42.6% (50.4M cases)
  2. Hypertension - 40.0% (47.4M cases)
  3. Obesity - 35.0% (41.4M cases)

### Economic Impact
- **Total Annual Cost:** 372.6 Billion EGP
  - Direct costs: 231.1B EGP
  - Indirect costs: 150.7B EGP
- **Productivity Loss:** 100.9 Billion EGP/year
- **DALYs Lost:** 6.48 Million years

### Risk Factors
- **Air Pollution:** 95% exposed (112.5M people)
- **Low Fruit/Vegetable Intake:** 85% (100.6M)
- **Physical Inactivity:** 74% (87.6M)
- **Overweight/Obesity:** 66% (78.1M)

### Egypt vs Global Average
- **Obesity:** 2.69x global average (35% vs 13%)
- **Diabetes Type 2:** 2.04x global average (22.4% vs 11%)
- **Hypertension:** 1.82x global average (40% vs 22%)

---

## 🗂️ Dataset Structure

The dashboard uses **12 interconnected CSV files**:

| File | Records | Description |
|------|---------|-------------|
| `1_diseases_prevalence.csv` | 33 | Main disease statistics |
| `2_age_distribution.csv` | 60 | Prevalence by age group |
| `3_gender_distribution.csv` | 22 | Male vs Female distribution |
| `4_risk_factors.csv` | 14 | Risk factor prevalence |
| `5_temporal_trends.csv` | 105 | 15-year trends (2010-2024) |
| `6_geographic_distribution.csv` | 20 | Governorate-level data |
| `7_economic_burden.csv` | 10 | Economic impact by category |
| `8_mortality_data.csv` | 13 | Annual deaths by disease |
| `9_comorbidity_matrix.csv` | 23 | Disease co-occurrence |
| `10_global_comparison.csv` | 7 | Egypt vs World |
| `11_disease_severity.csv` | 12 | Severity & disability scores |
| `12_treatment_access.csv` | 9 | Treatment costs & coverage |

**Total Records:** 348 data points

---

## 🛠️ Technologies Used

- **Power BI Desktop** - Data visualization and dashboard creation
- **Python 3.x** - Data generation and preprocessing
- **Pandas** - Data manipulation
- **DAX (Data Analysis Expressions)** - Advanced calculations
- **Power Query** - Data transformation

---

## 📥 How to Use

### Prerequisites
- Power BI Desktop (Download from [Microsoft](https://powerbi.microsoft.com/desktop/))
- Windows 10 or later

### Installation Steps

1. **Clone this repository:**
```bash
git clone https://github.com/YourUsername/Egypt-Chronic-Diseases-Dashboard.git
cd Egypt-Chronic-Diseases-Dashboard
```

2. **Open the dashboard:**
   - Navigate to `Dashboard/` folder
   - Double-click `Egypt_Chronic_Diseases.pbix`
   - Power BI Desktop will open automatically

3. **Refresh data (if needed):**
   - Click "Refresh" in Power BI
   - All CSV files will be reloaded from `Data/` folder

4. **Explore the dashboard:**
   - Use the navigation buttons to switch between pages
   - Apply filters using slicers (Category, Year, Gender, Region)
   - Click on visuals for drill-through details

---

## 📚 Documentation

- **[Data Dictionary](Documentation/Data_Dictionary.md)** - Complete description of all tables and columns
- **[DAX Measures](Documentation/DAX_Measures.md)** - All calculated measures with explanations
- **[Dashboard Guide](Documentation/Dashboard_Guide.md)** - Step-by-step usage instructions

---

## 📊 Data Sources

All data compiled from authoritative sources:

- **World Health Organization (WHO)** - EMRO STEPwise Survey 2024
- **International Diabetes Federation (IDF)** - Diabetes Atlas 2024
- **GLOBOCAN 2022** - Cancer incidence and mortality data
- **Egyptian Demographic and Health Survey (DHS) 2024**
- **World Bank** - Health statistics and economic indicators
- **Egyptian Medical Societies** - Cardiology, Nephrology, Hepatology

**Data Collection Period:** 2010-2024  
**Last Updated:** November 29, 2024  
**Egypt Population (2025):** 118,400,000

---

## 🎓 Use Cases

This dashboard is ideal for:

- **Healthcare Policymakers** - Resource allocation and priority setting
- **Researchers** - Epidemiological analysis and trend identification
- **Public Health Officials** - Disease surveillance and intervention planning
- **Healthcare Providers** - Understanding patient population characteristics
- **Students** - Learning data visualization and public health analytics
- **Media & Journalists** - Data-driven health reporting

---

## 📧 Contact

**Author:** Mariam Elaraby 
**Email:** marivull2811@gmail.com  
**LinkedIn:** (https://www.linkedin.com/in/mariamelaraby/) 

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Egyptian Ministry of Health and Population
- World Health Organization - Eastern Mediterranean Regional Office
- International Diabetes Federation
- All contributing medical societies and research institutions

---



**⭐ If you find this project helpful, please consider giving it a star!**
