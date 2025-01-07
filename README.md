# US-Accidental-Drug-Related-Deaths
A data mining project on accidental drug-related deaths in the US from 2012 to 2021

This repository contains my US Drug-Related Deaths Data Mining Project, which provides a comprehensive analysis of drug-related deaths across Connecticut between 2012 and 2021. This project is a demonstration of my data science skills, including preprocessing, exploratory data analysis (EDA), clustering, temporal analysis, and predictive modeling, and aims to highlight actionable insights for tackling the opioid epidemic.

---

## 📜 **Project Overview**

The project focuses on analyzing a dataset of drug overdose deaths to uncover patterns and trends across demographic, temporal, and geographic dimensions. Using a combination of data science techniques, the analysis aims to identify key risk factors and associations among various attributes such as age, gender, location, and drug type.

---

## 🚀 **Key Highlights**
1. **Data Preprocessing**:
   - Cleaned and transformed the dataset by handling missing values, splitting geographical attributes, and converting categorical features to numerical formats.
   - Extracted and processed critical features like `ResidenceCity`, `Cause of Death`, and `Age`.

2. **Exploratory Data Analysis (EDA)**:
   - Identified that **Fentanyl** and **opioids** were the leading causes of drug-related deaths.
   - Demographic insights revealed males aged 30-36 were most susceptible, while **Hispanics** and **White individuals** were disproportionately affected.

3. **Clustering**:
   - Applied **K-Means** clustering to numerical features, revealing clear and meaningful patterns among age, cause of death, and death location.
   - Explored categorical clustering but found limited interpretability.

4. **Temporal Analysis**:
   - Observed a 300% increase in drug-related deaths over the analyzed period.
   - Seasonal trends showed spikes during summer months and near holidays like Christmas, emphasizing the importance of targeted interventions.

5. **Association Rule Mining**:
   - Used **Apriori** and **FP-Growth** algorithms to identify common drug combinations responsible for fatalities.
   - Discovered that **Heroin, Cocaine, and Fentanyl** were the deadliest drugs both individually and in combination.

6. **Geospatial Analysis**:
   - Visualized death locations on an interactive map, highlighting cities like **Hartford** and **New Haven** as most affected.

7. **Forecasting**:
   - Applied time-series analysis using **SARIMAX**, uncovering trends but facing challenges with underfitting due to data characteristics.
  
---

## 🛠️ **Technologies Used**
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Statsmodels, Plotly
- **Algorithms**: K-Means, Apriori, FP-Growth, SARIMAX
- **Tools**: Jupyter Notebooks, GitHub

---

## 📊 **Key Findings**
- **Demographic Trends**: Vulnerable groups include males aged 30-36 and Hispanics.
- **Drug Insights**: Fentanyl and opioid-related deaths dominated the dataset, with heroin playing a significant role in fatal drug combinations.
- **Temporal Patterns**: Drug-related deaths have steadily risen, with seasonal spikes during warmer months and holidays.
- **Geographic Focus**: Hartford leads in drug-related fatalities, with interventions in cities like Stamford offering potential blueprints for success.

---

## 🌟 **Impact and Implications**

This project provides critical insights to aid policymakers, public health officials, and researchers in understanding and combating the opioid epidemic. It demonstrates my ability to analyze real-world data and develop actionable insights for societal challenges.

---

## 💡 **Future Directions**
-	Investigating the impact of COVID-19 on drug overdose trends.
- Developing predictive models for real-time monitoring of drug-related incidents.
- Exploring more advanced clustering and time-series forecasting techniques to improve insights.

---

## 🔗 **Portfolio & Contact**

This project is part of my Data Science Portfolio, showcasing my expertise in tackling real-world problems using data science. For any inquiries or collaborations, feel free to reach out via:
-	Email: shayan.raja123@gmail.com
- LinkedIn: https://www.linkedin.com/in/shayanraja
