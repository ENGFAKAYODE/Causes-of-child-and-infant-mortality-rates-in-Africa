# CAUSES OF CHILD AND INFANT MORTALITY RATE IN AFRICA

## TABLE OF CONTENT
- [GENERAL OVERVIEW](#general-overview)
- [OBJECTIVE](#objective)
- [DATA SOURCE](#data-source)
- [DATA TOOLS](#data-tools)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [DATA ANALYSIS](#data-analysis)
- [RECOMMENDATION](#recommendation)

## GENERAL OVERVIEW

Child and infant mortality rates remain a critical issue in Africa, impeding progress toward several Sustainable Development Goals (SDGs), including Goal 3: Good Health and Well-being. By leveraging data-driven approaches, this hackathon aims to identify actionable insights, develop innovative solutions, and contribute to global efforts to reduce preventable deaths in children under five years of age. Objective The primary objective is to utilize the provided datasets to uncover patterns, correlations, and key drivers of child and infant mortality in African countries. Participants will propose data-driven strategies and interventions that policymakers, healthcare providers, and organizations can adopt to improve health outcomes for children.

## OBJECTIVE

The primary objective is to utilize the provided datasets to uncover patterns, correlations, and key drivers of child and infant mortality in African countries. This project will propose data-driven strategies and interventions that policymakers, healthcare providers, and organizations can adopt to improve health outcomes for children.

1. Identify socioeconomic, healthcare, and environmental factors contributing to high mortality rates.
2. Propose actionable recommendations to address gaps in vaccination coverage, healthcare access, and maternal support.
3. Present insights in a format that is understandable to a non-technical audience.

## DATA SOURCE

The primary data source for this analysis is obtained from government health records, demographic surveys, and publicly available databases such as WHO and UNICEF reports.

#### They include:
- **Health Protection Coverage**: Percentage of populations covered by health insurance.
- **Global Vaccination Coverage:** Vaccination rates for various diseases among children.
- **Births Attended by Skilled Health Staff**: The percentage of births assisted by skilled healthcare providers.
- **Maternal Deaths by Region**: Estimated maternal deaths by region and year.
- **Child Mortality by Income Level**: Under-five mortality rates across different income-level countries.
- **Infant Deaths**: Annual number of infant deaths by country.
- **Youth Mortality Rates**: Mortality rates for individuals under 15.
- **Causes of Death in Children Under Five**: Breakdown of major causes of death among young children.

## DATA TOOLS

- **Microsoft Excel:** Used for initial data storage, cleaning and basic analysis.
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn):** For data cleaning, transformation, processing and visualization.

## DATA CLEANING STEPS:
   - Renamed Columns
   - Removed duplicates
   - Removed completely empty, <50% null and unnecessary columns
   - Corrected inconsistent data format and missing values
   - Checked for skewness to determine whether to fill missing values with median or mean, all columns are left-skewed so I filled missing values with the median. 
     
# DATA TRANSFORMATION
   - Merged the datasets into a dataframe
   - Create a new column with the average of all immunization factors
   - Exported the merged data to CSV file view so that the file can be explored in Excel

## EXPLORATORY DATA ANALYSIS (EDA)

- Assessing data quality and handling missing values.
- Identifying key trends, patterns and anomalies in mortality rates.
- Conducting descriptive statistics to understand distribution and variance.
- Visualizing data using charts, histograms, and scatter plots to identify relationships.

## DATA ANALYSIS

- **Trend Analysis:** Examining historical child mortality rates to understand long-term patterns.
- **Correlation Analysis:** Identifying relationships between mortality rates and factors such as healthcare access, maternal education and economic status.

## RECOMMENDATION

- Improve maternal and child healthcare services by increasing access to prenatal and postnatal care.
- Enhance vaccination programs to cover vulnerable populations more effectively.
- Strengthen public health campaigns to educate communities on child healthcare and hygiene.
- Use data-driven insights to allocate healthcare resources efficiently and target high-risk regions.
