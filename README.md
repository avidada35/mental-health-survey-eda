# **Mental Health in Tech — Exploratory Data Analysis & Dashboard**
A comprehensive exploratory data analysis (EDA) and interactive dashboard analyzing mental health trends in the tech industry using survey data. The project uncovers key factors influencing treatment-seeking behavior and workplace mental health dynamics.
---
## Detailed Overview

This project analyzes the Mental Health in Tech Survey (2014) dataset to understand how workplace conditions, demographics, and organizational factors influence mental health and treatment-seeking behavior among tech professionals.

The workflow includes:

Data cleaning and preprocessing
Univariate and bivariate analysis
Correlation and feature importance exploration
Geographic insights
Interactive dashboard visualization

The final output is a data-driven analytical pipeline complemented by a modern, interactive dashboard for intuitive exploration of insights.

## Problem Statement

Mental health in the tech industry is often under-discussed despite its growing importance. Organizations lack clear visibility into:

How workplace factors impact mental health
What drives employees to seek treatment
The role of stigma and organizational support
Geographic variations in mental health trends

This project aims to extract actionable insights from survey data to better understand these dynamics.

## Solution Approach

1. Data Cleaning & Preprocessing
Handled missing values using mode imputation for key categorical features
Removed invalid or extreme age values (filtered to 18–75)
Standardized categorical variables (e.g., gender normalization)
Dropped irrelevant columns (e.g., timestamps, comments)
2. Exploratory Data Analysis (EDA)
Univariate Analysis
Age distribution, gender breakdown
Treatment rates and family history trends
Bivariate Analysis
Treatment vs gender, family history, work interference
Workplace factors vs mental health outcomes
Correlation Analysis
Label encoding of categorical variables
Heatmap to identify strongest predictors of treatment
3. Feature Insights
Identified key drivers of treatment-seeking behavior
Highlighted workplace-related predictors (e.g., work interference)
4. Geographic Analysis
Country-wise treatment rates
Comparison of stigma vs employer support
Regional patterns in mental health awareness
5. Interactive Dashboard
Built using Plotly for dynamic visualization
Includes:
KPI cards (respondents, treatment rate, top predictors)
Feature importance visualization
Treatment distribution by demographics
Workplace and organizational insights

## Tech Stack
Programming Language: Python

Libraries:
Pandas, NumPy (data processing)

Matplotlib, Seaborn (visualization)

Plotly (interactive dashboard)

Scikit-learn (encoding, analysis)

Frontend Dashboard: HTML + Plotly.js

Environment: Google Colab / Jupyter Notebook

## Installation & Setup

1. Clone Repository
git clone https://github.com/your-username/mental-health-tech.git
cd mental-health-tech
2. Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn plotly
3. Run Analysis
python scripts/mental_health_survey.py
4. Launch Dashboard

## **Open in browser:**

dashboard/mental_health_dashboard.html


## Usage Instructions
Place the dataset (survey.csv) in the project directory
Run the Python script to:
Clean data
Generate plots
Produce insights
Open the HTML dashboard to explore:
Key metrics
Feature importance
Treatment trends

## Results / Output
Cleaned dataset ready for analysis
Multiple analytical visualizations:
Age & gender distribution
Treatment vs workplace factors
Correlation heatmap
Key insights:
Work interference strongly correlates with treatment-seeking
Family history is a significant factor
Workplace stigma impacts willingness to discuss mental health
Interactive dashboard with:
KPI summaries
Feature importance visualization
Demographic and organizational insights

## Future Improvements
Add predictive modeling (classification for treatment prediction)
Deploy dashboard using Streamlit or Dash
Integrate real-time or updated survey datasets
Enhance UX with filters and drill-down analytics
Perform deeper NLP analysis on open-text responses

## Author

AVIRAJ VIRAPE

## Contributing

Contributions are welcome.
Fork the repository
Create a feature branch
Commit changes
Open a pull request

## License

This project is licensed under the MIT License.
