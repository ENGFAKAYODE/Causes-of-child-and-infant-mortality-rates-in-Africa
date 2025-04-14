# CAUSES OF CHILD AND INFANT MORTALITY RATE IN AFRICA

## TABLE OF CONTENT
- [GENERAL OVERVIEW](#general-overview)
- [OBJECTIVE](#objective)
- [SKILLS DEMONSTRATED](#skills-demonstrated)
- [DATA SOURCE](#data-source)
- [DATA TOOLS](#data-tools)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [DATA ANALYSIS](#data-analysis)
- [RECOMMENDATION](#recommendation)

## GENERAL OVERVIEW

Child and infant mortality rates remain a critical issue in Africa, impeding progress toward several Sustainable Development Goals (SDGs), including Goal 3: Good Health and Well-being. By leveraging data-driven approaches, this hackathon aims to identify actionable insights, develop innovative solutions, and contribute to global efforts to reduce preventable deaths in children under five years of age. Objective The primary objective is to utilize the provided datasets to uncover patterns, correlations, and key drivers of child and infant mortality in African countries. Participants will propose data-driven strategies and interventions that policymakers, healthcare providers, and organizations can adopt to improve health outcomes for children.

## OBJECTIVE

The primary objective is to utilize the provided datasets to uncover patterns, correlations, and key drivers of child and infant mortality in African countries. This project will propose data-driven strategies and interventions that policymakers, healthcare providers, and organizations can adopt to improve health outcomes for children.

1. Identify socioeconomic, healthcare and environmental factors contributing to high mortality rates.
2. Propose actionable recommendations to address gaps in vaccination coverage, healthcare access, and maternal support.
3. Present insights in a format that is understandable to a non-technical audience.

## SKILLS DEMONSTRATED
- Data Cleaning 
- Data Visualisation
- Exploratory Data Analysis
- Problem-solving
- Data Transformation

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
     
## DATA TRANSFORMATION
   - Merged the datasets into a dataframe
   - Create a new column with the average of all immunization factors
   - Exported the merged data to CSV file view so that the file can be explored in Excel

## DATA MODELLING
   - The datasets were merged into a dataframe, so there was no need for data modelling

## EXPLORATORY DATA ANALYSIS (EDA)

- Assessed data quality.
- Identified key trends, patterns and anomalies in mortality rates.
- Conducted descriptive statistics to understand distribution and variance.
- Visualized data using charts, histograms, and scatter plots to identify relationships.

## DATA ANALYSIS

- **Trend Analysis:** Examining historical child mortality rates to understand long-term patterns.
- **Correlation Analysis:** Identifying relationships between mortality rates and factors such as healthcare access, skilled health staff, wealth quintile, etc.

## INSIGHTS

### 1. Socioeconomic Factors
a. **Poverty and Wealth Inequities:** The "Very Poor" wealth group has the highest number of deaths. The heatmap indicates a strong negative correlation between the wealth quintile and mortality rates (e.g., -0.46). Wealthier populations have better access to healthcare, nutrition and education. Poverty leads to poor living conditions, malnutrition and inability to afford health services.

b. **Health Insurance Coverage:** Low insurance coverage (-0.26 correlation with under-fifteen mortality) limits access to essential maternal and infant healthcare services. This exacerbates disparities between socioeconomic groups.

c. **Education and Awareness:** Lack of education especially among mothers, reduces awareness of proper child care, hygiene and vaccination importance. Correlation between wealth and maternal health outcomes highlights that uneducated or impoverished communities are at a greater risk.

### 2. Healthcare Factors
a. **Inadequate Access to Skilled Birth Attendants:** The strong negative correlation (-0.50) between skilled health staff attendance and mortality rates indicates that many births occur without professional care. Poor infrastructure and insufficient healthcare personnel contribute to preventable deaths during birth.

b. **Maternal Health Support:** Correlation between maternal deaths and infant mortality (+0.88) indicates poor maternal health has a direct impact on child survival rates. Lack of prenatal and postnatal care increases risks for birth complications and premature births.

c. **Insufficient Vaccination Coverage:** Vaccine-preventable diseases like measles, tetanus, meningitis and malaria (mentioned in the causes of death) remain prevalent in regions with limited vaccination programs. It has a correlation of (-0.52) with the overall deaths

d. **Overburdened and Underfunded Health Systems:** Limited funding, equipment shortages and overburdened facilities in rural and poor areas reduce the quality of care.

## RECOMMENDATION

### 1. Address Gaps in Vaccination Coverage
**Challenge Identified:** High mortality from vaccine-preventable diseases such as measles, tetanus, and meningitis.

**Solutions:**
- **Strengthen Immunization Programs:**
Scale up outreach programs to reach remote and underserved areas.
Deploy mobile vaccination clinics in rural areas where healthcare facilities are lacking.
- **Improve Vaccine Supply Chain Management:**
Ensure cold chain logistics for proper vaccine storage and distribution.
Reduce stockouts by implementing real-time monitoring systems.
- **Community Engagement and Education:**
Conduct awareness campaigns to combat vaccine hesitancy and misinformation.
Partner with community leaders to promote immunization programs.
- **Incentivize Vaccination:**
Provide incentives such as food packages or childcare essentials for families completing immunization schedules.

### 2. Improve Healthcare Access
**Challenge Identified:** Limited healthcare infrastructure, shortage of skilled health workers and poor access in remote regions.

**Solutions:**
- **Expand Health Infrastructure:**
Build and upgrade primary healthcare facilities in underserved areas.
Invest in telemedicine to connect remote areas with specialized medical services.
- **Train and Deploy Skilled Health Workers:**
Increase training for community health workers to deliver essential care.
Incentivize health professionals (e.g., higher salaries, housing benefits) to work in rural areas.
- **Improve Affordability of Healthcare:**
Introduce health insurance schemes tailored for low-income families.
- **Provide free or subsidized healthcare for children and pregnant women.**
- **Enhance Maternal and Neonatal Support**


**Challenges Identified**: High mortality due to birth asphyxia, prematurity, and sepsis, indicating inadequate maternal care.

Solutions:

- **Strengthen Antenatal and Postnatal Care:**
Ensure all pregnant women attend at least four antenatal visits for proper monitoring.
Promote early postnatal check-ups to prevent complications for mothers and newborns.
- **Ensure Skilled Birth Attendance:**
Scale up training and deployment of midwives and skilled birth attendants.
Encourage facility-based deliveries through maternal incentives (e.g. free delivery kits).
- **Promote Family Planning and Reproductive Health:**
Expand access to contraceptives to reduce high-risk pregnancies.
Offer reproductive health education to empower women and families.
- **Address Nutrition and Anemia:**
Provide iron supplements and balanced nutrition programs for expectant mothers.
Promote breastfeeding and support proper infant nutrition.

### Other Recommendations:
- **Data Collection and Monitoring:**
Implement systems for real-time data collection on vaccination rates, maternal health, and infant mortality to identify gaps quickly.
- **Collaborate with International Partners:**
Leverage support from organizations like WHO, UNICEF, and other global health partners to fund and implement large-scale health initiatives.
- Promote Clean Water and Sanitation
- Improve access to clean water to combat diarrheal diseases. e. Educate communities on hygiene and sanitation practices.
