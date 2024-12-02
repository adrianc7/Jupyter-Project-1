# Key Indicators of Life Expectancy in Developing Countries

**Author**: Adrian Chavez-Loya  
**Completion Date**: June 2024  

---

## Overview
This project explores key factors affecting life expectancy in developing countries, based on data from the **World Health Organization (WHO)** and **United Nations**. Using regression modeling techniques, the analysis identifies significant health and economic indicators that contribute to life expectancy variations across 193 countries between 2000 and 2015.

---

## Objective
The primary goal of this project is to identify actionable insights for improving life expectancy in developing countries. This is achieved through a series of statistical models that assess the relationship between life expectancy and various predictors, including healthcare expenditure, vaccination rates, economic indicators, and more.

---

## Dataset
- **Name**: Life Expectancy Data  
- **Source**: Global Health Observatory (WHO), UN economic data  
- **Period**: 2000–2015  
- **Scope**: Developing countries  
- **Variables**: Includes 22 features such as GDP, infant mortality, vaccination rates, and education levels.

---

## Analysis Highlights

### Models
1. **Model 1**: Relationship between GDP and Life Expectancy  
   - Explores a linear and quadratic relationship.  
   - Shows GDP's diminishing returns on life expectancy.

2. **Model 2**: Comprehensive Analysis of All Predictors  
   - Identifies significant predictors like Adult Mortality, Schooling, and HIV/AIDS prevalence.  
   - High explanatory power (**R² = 82.5%**) but suffers from multicollinearity.

3. **Model 3**: Optimized Model Excluding GDP and Percentage Expenditure  
   - Retains robust explanatory power (**R² = 81.9%**).  
   - Highlights the most impactful predictors while resolving multicollinearity.

### Key Predictors
- **Positive Influences**: Schooling, BMI, Income Composition of Resources, Vaccination Coverage (Diphtheria).  
- **Negative Influences**: Adult Mortality, Infant Mortality, HIV/AIDS prevalence.  
- **Moderate Influences**: Alcohol consumption, Polio and Hepatitis B vaccination rates.

---

## Key Findings
- Education and equitable resource distribution are pivotal for increasing life expectancy.  
- Preventive healthcare, especially vaccination coverage, plays a vital role.  
- Addressing diseases like HIV/AIDS and reducing child mortality are critical priorities.  

---

## Technologies Used
- **Programming Languages**: Python  
- **Libraries**: `pandas`, `numpy`, `statsmodels`, `matplotlib`, `seaborn`  
- **Statistical Techniques**: Linear Regression, Quadratic Modeling, Multicollinearity Analysis (VIF)
