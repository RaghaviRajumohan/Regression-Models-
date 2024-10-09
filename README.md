# Prediction Models Repository

## Overview
In this project, I developed a predictive model for housing prices using Ordinary Least Squares (OLS) multiple regression. The project involved applying feature engineering techniques such as One-Hot Encoding and scaling to prepare the data for modeling. Various regression models, including Simple Linear Regression, Multiple Linear Regression, Polynomial Regression, and Logit Regression, were tested and compared using performance metrics like R-squared, adjusted R-squared, and Mean Squared Error (MSE).

Cross-validation was employed to evaluate the models' generalizability, and the most optimal model was selected based on overall performance and prediction accuracy. The goal was to create a reliable model capable of predicting housing prices using key factors such as location, square footage, and market trends.

### Key Steps and Techniques:

#### Data Preprocessing:
- **Data Loading & Cleaning**: Loaded the housing dataset and addressed missing values by imputing with the median for numerical features and the mode for categorical features, ensuring the dataset was clean and ready for analysis.
- **Encoding Categorical Variables**: Applied One-Hot Encoding to convert categorical variables like neighborhood and house style into binary form, which allowed the regression model to process these features.
- **Scaling Features**: Used MinMaxScaler to scale continuous variables like house size and price to a range between 0 and 1, normalizing data to improve model convergence and performance.
- **Exploratory Data Analysis**: Generated Cullen and Frey plots to explore the data distribution and variability of features, identifying patterns such as skewness and kurtosis that informed feature selection and model assumptions.

#### Feature Selection:
- **Correlation Analysis**: Conducted correlation matrix analysis to identify highly correlated features with the target variable (housing price). This step reduced multicollinearity, improving the model’s interpretability.
- **Boruta Algorithm**: Implemented the Boruta Algorithm to rank the importance of features, eliminating irrelevant features while retaining those that contributed the most predictive power to the model.
- **Multicollinearity Check**: Calculated the Variance Inflation Factor (VIF) for each feature to detect multicollinearity. Features with a VIF above 10 were removed or combined to reduce redundancy and improve model stability.

#### Model Development:
- **Model Selection**: Developed and compared multiple regression models, including:
  - **Simple Linear Regression** to establish a baseline prediction using only one feature.
  - **Multiple Linear Regression** to account for interactions between multiple features affecting housing price.
  - **Polynomial Regression** to capture non-linear relationships between features and the target variable.
  - **Logit Regression** to evaluate the probability of houses falling into different price ranges (useful for classification scenarios).
- **Model Comparison**: Models were compared based on interpretability, as well as performance metrics like R-squared, adjusted R-squared, and Mean Squared Error (MSE). This ensured that the chosen model was both accurate and suitable for the business objectives.

#### Model Evaluation:
- **Cross-Validation**: Performed k-fold cross-validation to assess model generalizability and prevent overfitting. The dataset was split into training and test sets multiple times, allowing robust evaluation on unseen data.
- **Performance Metrics**: Calculated Mean Squared Error (MSE) to quantify the model’s predictive error and R-squared to measure the proportion of variance explained by the model. These metrics were crucial for determining how well the model would perform in predicting housing prices.
- **Bootstrapping**: Applied bootstrapping techniques to generate multiple samples from the dataset, testing the model’s consistency and reliability across various sample distributions.

#### Visualization:
- **Data Visualization**: Used Matplotlib and Seaborn to create a variety of plots to visualize relationships between features and the target variable. This included:
  - **Box plots** and **histograms** to show feature distribution and outliers.
  - **Regression plots** to demonstrate the linear relationship between selected features and housing price.
  - **Residual plots** to evaluate model accuracy by analyzing the differences between predicted and actual values.
- **Model Results Visualization**: Generated detailed plots showing the performance of different models, enabling stakeholders to understand the model's behavior and make informed decisions.

#### Technical Skills:
- **Python**: Utilized Python for data manipulation, statistical analysis, and model development, leveraging its libraries to create a streamlined workflow.
- **Pandas**: Used Pandas for efficient data wrangling, cleaning, and manipulation of large datasets.
- **Scikit-learn**: Applied Scikit-learn for model development, feature selection, cross-validation, and model evaluation techniques.
- **NumPy**: Leveraged NumPy for fast numerical operations and matrix computations to ensure efficient handling of large datasets.
- **Matplotlib & Seaborn**: Used these libraries to create detailed visualizations for data analysis and model interpretation.

#### Final Takeaways:
This project highlighted the complete process of building a regression model, from feature engineering and data preprocessing to model evaluation and selection. Advanced techniques such as cross-validation, bootstrapping, and feature selection ensured that the final model was both reliable and interpretable. By focusing on model robustness and performance, I developed a predictive tool that provides valuable insights for decision-making in real estate investment.
