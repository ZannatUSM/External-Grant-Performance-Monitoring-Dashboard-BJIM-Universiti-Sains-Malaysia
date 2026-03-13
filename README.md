# External Grant Performance Monitoring Dashboard and Prediction for BJIM

##  Project Overview
This project focuses on enhancing the monitoring and forecasting of external grants for **Pejabat Bahagian Jaringan Industri & Masyarakat (BJIM)** at Universiti Sains Malaysia (USM). By transitioning from manual data handling to a centralized dashboard and predictive modeling, the project enables data-driven decision-making and optimized resource planning for university-industry collaborations.

##  Objectives
* **Centralized Monitoring:** Developed an interactive Power BI dashboard to track grant performance across 53 different communities and industries.
* **Predictive Analytics:** Built machine learning models to forecast future grant volumes and funding trends.
* **Data Optimization:** Processed and structured 5 years (2019-2024) of historical grant data to identify key funding drivers.

## 🛠️ Tech Stack & Methodology
The project follows the standard **Data Science Life Cycle**:

* **Data Processing:** Python (Pandas, Polars)
* **Machine Learning:** Scikit-learn (ElasticNet, Gradient Boosting, Random Forest)
* **Visualization:** Power BI
* **Model Interpretation:** SHAP (SHapley Additive exPlanations)

### Workflow:
1.  **Data Preparation:** Cleaning, translating (Malay to English), and structuring raw institutional data.
2.  **Exploratory Data Analysis (EDA):** Identifying funding growth (e.g., 10% increase from 2022 to 2023).
3.  **Feature Engineering:** Utilizing `SelectKBest` and `GridSearchCV` for hyperparameter tuning.
4.  **Modeling:** Comparative analysis between regression and classification models.

##  Key Results
* **Total Grant Volume:** RM 20,118,979.68 (2022-2024).
* **Best Model:** **ElasticNet Regression** achieved the highest stability and accuracy with an **R² of 0.98**.
* **Model Insights:** Gradient Boosting achieved an **R² of 0.75**, providing clear insights into funding factors like project duration and investigator ratings.

##  Challenges
* **Data Quality:** Addressed missing funding records and inconsistent manual entries.
* **Data Imbalance:** High-value grants are sparse, which creates challenges for regression accuracy in outlier cases.

##  Author
* **Zannatul Sanzida** (P-COM0145/22)
* **Supervisor:** Dr. Nasuha Lee Abdullah
* **Organization:** BJIM, Universiti Sains Malaysia (USM)

---
*This project was completed as part of a professional practicum at USM.*
