# Exploratory Data Analysis (EDA) on Customer Churn Dataset

## Overview
This project focuses on **Exploratory Data Analysis (EDA)** for a telecom customer dataset. The objective is to uncover key insights about customer behavior, service usage, and churn factors using various statistical techniques and visualizations.

## Dataset
- **Total Records:** 7,043
- **Total Features:** 21
- **Key Columns:**
  - Customer Demographics: Gender, Senior Citizen, Partner, Dependents
  - Service Subscriptions: Phone Service, Internet Service, Streaming Services
  - Account Information: Contract Type, Payment Method, Tenure, Charges
  - Churn Label: Indicates whether a customer left the service

## Key Findings
- **Churn Rate:** ~27% of customers have churned.
- **Contract Type:**
  - Month-to-month contracts have the highest churn rate (~45%).
  - Two-year contracts have the lowest churn rate (~3%).
- **Service Impact:**
  - Customers with bundled services have a lower churn rate (~15%).
  - Fiber optic internet users tend to churn more than DSL users.
- **Financial Insights:**
  - Churned customers have higher average monthly charges (~$74) compared to retained customers (~$61).
  - Customers with electronic check payments have a significantly higher churn rate (~42%).

## Analysis & Visualizations
- **Data Cleaning & Preprocessing:** Handled missing values and outliers.
- **Descriptive Statistics:** Summarized numerical and categorical distributions.
- **Correlation Analysis:** Identified key relationships using heatmaps.
- **Churn Trends:** Used bar charts, pie charts, and histograms to visualize factors affecting churn.

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **Jupyter Notebook** for interactive analysis

## Future Improvements
- Perform **predictive modeling** using Machine Learning.
- Introduce **feature engineering** for better insights.
- Expand dataset analysis with external sources.

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## Author
- **Ruchira More** ([GitHub Profile](https://github.com/ruchiraaa04))

## License
This project is open-source under the **MIT License**.

