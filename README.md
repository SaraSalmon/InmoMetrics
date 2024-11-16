# House Price Prediction in King County 🏡

## Project Description
This project was developed as part of a Bootcamp exercise simulating work in a data consultancy firm. Our client, a real estate company in King County, aimed to:

1. Identify the variables that have the most significant influence on house prices.
2. Build a predictive model to estimate house prices based on property characteristics.
3. Analyze the features of houses priced above $650,000 to uncover trends and insights.

---

## Objectives
- Conduct an exploratory data analysis (EDA) to better understand the dataset and relationships between variables.
- Preprocess and clean the data for optimal machine learning performance.
- Implement various machine learning models to predict house prices and evaluate their performance.
- Study properties priced above $650,000 to identify key factors influencing high-value homes.

---

## Technologies Used
- **Python**: Core language for analysis and modeling.
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation and analysis.
  - `matplotlib`, `seaborn`: Data visualization.
  - `scikit-learn`, `xgboost`: Machine learning algorithms and tools.
- **Jupyter Notebook**: For documenting and implementing analysis.

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- **Correlation Matrix and Heatmap**: A thorough correlation analysis was conducted to identify relationships between variables and check for multicollinearity.
- **Visualizations**: Plots were used to explore the distribution of house prices and other key features.
- **Insights on High-Value Homes**: A specific analysis of houses priced above $650,000 revealed trends related to location, size, and year built.

### 2. Data Preprocessing
- **Data Cleaning**: Removal of null values, duplicates, and outliers.
- **Feature Engineering**: Transforming categorical variables and creating new meaningful features.
- **Scaling and Transformation**:
  - Applied **MinMaxScaler**, **StandardScaler**, and **Log Transform** to standardize numerical features and improve model performance.

### 3. Machine Learning Models
We trained and tested several machine learning models to predict house prices:
- **Linear Regression**: A baseline model to evaluate linear relationships.
- **Ridge and Lasso Regression**: Regularized linear models to address multicollinearity.
- **Decision Tree Regressor**: A non-linear approach to capture complex patterns.
- **K-Nearest Neighbors (KNN)**: A distance-based prediction model.
- **XGBoost**: A high-performance ensemble method.

### 4. Model Evaluation
- The models were evaluated using metrics such as:
  - **R²**: Coefficient of determination.
  - **RMSE**: Root Mean Squared Error.
- Comparisons were made to identify the best-performing models before and after standardization.

---

## Results
- **Key Variables**: The most influential factors included the size of the house, location (zipcode), number of bathrooms, and lot size.
- **Top Model**: XGBoost achieved the highest R² score after applying StandardScaler, outperforming other models in prediction accuracy.
- **High-Value Homes**: Properties priced above $650,000 are predominantly located in areas near Seattle and Bellevue, characterized by larger lot sizes and recent construction dates.

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
