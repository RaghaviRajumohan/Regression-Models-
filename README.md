# Prediction Models Repository

## Overview
This repository highlights a series of projects that utilize advanced data science techniques, statistical modeling, and machine learning to address diverse real-world challenges. The projects emphasize end-to-end workflows, from data preprocessing and feature engineering to model evaluation and visualization. The following sections detail the steps and methods employed across these projects.

### Key Projects:

#### **1. Housing Price Prediction**
This project involved developing a predictive model for housing prices using Ordinary Least Squares (OLS) multiple regression, supplemented with advanced feature engineering and statistical evaluation. Key highlights include:
- **Modeling Techniques**: Simple Linear Regression, Multiple Linear Regression, Polynomial Regression, and Logit Regression were employed and compared.
- **Performance Metrics**: R-squared, adjusted R-squared, and Mean Squared Error (MSE) were used for evaluation.
- **Generalizability**: Cross-validation and bootstrapping techniques ensured robust model performance.

#### **2. Uber and Public Transit Impact Analysis**
An exploration of the relationship between Uber's presence and public transit ridership using:
- **Statistical Models**: OLS, PanelOLS, LASSO regression, and Double-LASSO regression.
- **Advanced Techniques**: Log transformations, interaction terms, and entity-time fixed effects to address nuanced dynamics.
- **Visualization**: Regression plots and residual analyses were employed to ensure model interpretability.

#### **3. BLP Modeling for Pizza Market Analysis**
This project employed the Berry-Levinsohn-Pakes (BLP) demand estimation framework to analyze competition and market dynamics in the pizza delivery market. Key components included:
- **Econometric Techniques**: Applied Nonlinear Regression, Instrumental Variables (IV) Regression, and fixed effects modeling to estimate consumer preferences and substitution patterns.
- **Market Insights**: Evaluated the impact of pricing, product differentiation, and market characteristics on consumer demand.
- **Performance Metrics**: Assessed model fit using log-likelihood and out-of-sample prediction accuracy, providing robust demand estimates for strategic decision-making.
- 
#### **4. Double LASSO Regression Models**
A comprehensive analysis of variable selection and causal inference using:
- **Double LASSO Approaches**: Implementations included Cross-Fitted Double-LASSO for robust feature selection.
- **Simulation Studies**: Performance was validated through Mean Squared Error (MSE) calculations and statistical comparisons.

#### **5. Automated Cloud-Based Models**
This project integrated machine learning models into Google Cloud Functions to enable scalable automation, including:
- **Real-Time Predictions**: Models deployed for property valuation using Scikit-learn.
- **Web Scraping**: Automated data collection pipelines for real-time updates.

---

### Technical Tools and Skills:
- [![Python](https://img.shields.io/badge/Code-Python-blue)]()
- [![Scikit-learn](https://img.shields.io/badge/Library-Scikit--learn-orange)]()
- [![Pandas](https://img.shields.io/badge/Data-Pandas-yellow)]()
- [![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green)]()
- [![Google Cloud](https://img.shields.io/badge/Cloud-Google%20Cloud-lightblue)]()
- [![Statsmodels](https://img.shields.io/badge/Stats-Statsmodels-brightgreen)]()
- [![NumPy](https://img.shields.io/badge/Math-NumPy-purple)]()
- [![Beautiful Soup](https://img.shields.io/badge/Web%20Scraping-Beautiful%20Soup-yellowgreen)]()
- [![Requests](https://img.shields.io/badge/Web%20Scraping-Requests-blue)]()
- [![Selenium](https://img.shields.io/badge/Web%20Scraping-Selenium-orange)]()


---

### Detailed Project Workflow:

#### **Data Preprocessing**
- **Cleaning and Transformation**: Addressed missing values using appropriate imputation techniques and normalized continuous variables for improved model performance.
- **Feature Engineering**: Created derived variables such as interaction terms, log transformations, and One-Hot Encodings to capture nuanced relationships in the data.
- **Exploratory Data Analysis (EDA)**: Visualized and assessed data distributions, identified patterns, and ensured compatibility with modeling techniques.

#### **Feature Selection**
- **Correlation Analysis**: Used correlation matrices to identify relationships and reduce redundancy.
- **Dimensionality Reduction**: Applied algorithms like Boruta and Double-LASSO to select impactful features while minimizing noise.

#### **Model Development**
- **Model Variety**: Implemented diverse models, including regression (OLS, LASSO, and Polynomial), classification, and machine learning approaches tailored to the problem.
- **Scalability**: Optimized models for deployment in cloud environments using scalable frameworks like Google Cloud Functions.

#### **Model Evaluation**
- **Performance Metrics**: Evaluated using R-squared, Mean Squared Error (MSE), and other appropriate measures.
- **Validation Techniques**: Employed cross-validation, bootstrapping, and residual analyses to ensure robust and generalizable results.

#### **Visualization**
- **Data Insights**: Generated visualizations such as box plots, regression plots, and residual plots to communicate findings clearly.
- **Model Comparisons**: Used visual tools to compare model performance, aiding in stakeholder understanding and decision-making.

---

### Final Takeaways:
This repository demonstrates a mastery of data science workflows, combining statistical rigor with machine learning methodologies. Each project highlights practical solutions and interpretable results, emphasizing technical precision, automation, and actionable insights.
