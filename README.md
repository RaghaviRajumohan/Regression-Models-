# Prediction Models Repository

## Overview
In this project, I developed a predictive model for housing prices using Ordinary Least Squares (OLS) multiple regression. The project involved applying feature engineering techniques such as One-Hot Encoding and scaling to prepare the data for modeling. Various regression models, including Simple Linear Regression, Multiple Linear Regression, Polynomial Regression, and Logit Regression, were tested and compared using performance metrics like R-squared, adjusted R-squared, and Mean Squared Error (MSE).

Cross-validation was employed to evaluate the models' generalizability, and the most optimal model was selected based on overall performance and prediction accuracy. The goal was to create a reliable model capable of predicting housing prices using key factors such as location, square footage, and market trends.

### Key Steps and Techniques:

#### Data Preprocessing:
- Loaded and cleaned the dataset, handling missing values and encoding categorical variables using One-Hot Encoding.
- Applied scaling techniques to normalize continuous variables, ensuring consistent input for the regression model.
- Used Cullen and Frey plots for exploratory data analysis, identifying key trends and distributions in the dataset.

#### Feature Selection:
- Conducted an in-depth correlation analysis to identify the most significant features affecting housing prices.
- Implemented the Boruta Algorithm to select and rank important features, ensuring that only relevant variables were included in the model.
- Examined multicollinearity using the Variance Inflation Factor (VIF) to further refine the input features.

#### Model Development:
- Developed several competing regression models, including:
  - Simple Linear Regression
  - Multiple Linear Regression
  - Polynomial Regression
  - Logit Regression
- Chose the final model based on performance metrics and interpretability, ensuring it met the business needs.

#### Model Evaluation:
- Validated the model using cross-validation techniques, ensuring robust performance on unseen data.
- Evaluated model performance using metrics such as Mean Squared Error (MSE) and R-squared to assess accuracy and goodness of fit.
- Conducted bootstrapping to further test model stability and robustness across different samples.

#### Visualization:
- Utilized Matplotlib and Seaborn to visualize the relationship between features and target variables, highlighting key trends and residuals.
- Generated detailed plots such as box plots, histograms, and regression plots to visually evaluate the model’s performance.

#### Technical Skills:
- **Python** for data manipulation, modeling, and visualization
- **Pandas** for efficient data wrangling
- **Scikit-learn** for model development and evaluation
- **NumPy** for numerical operations and matrix computations
- **Matplotlib** and **Seaborn** for data visualization

This project demonstrated the ability to handle end-to-end regression modeling workflows, from data preprocessing and feature engineering to model validation and performance evaluation. By incorporating advanced feature selection methods and robust evaluation techniques, I was able to build a reliable predictive model for housing prices, providing actionable insights for decision-making processes in real estate investment.


## Technologies and Tools Used
- **Programming Languages:** Python
- **Libraries and Frameworks:** 
  - Data Analysis: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn, XGBoost, Boruta
  - Model Deployment: Flask (or Streamlit)
- **Development Tools:** Jupyter Notebook, VS Code
- **Version Control:** Git, GitHub
