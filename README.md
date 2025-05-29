Task 3: Linear Regression - Housing Price Prediction

 📄 Overview
This notebook demonstrates a simple linear regression model to predict house prices based on area using the Housing Price Prediction dataset. It includes:
- Data preprocessing
- Model training and evaluation
- Visualization
- Interpretation of regression results

 📊 Dataset
- Dataset Source: Housing Price Prediction (Kaggle)
- Target Variable: `price`
- Feature Used: `area`

 🔧 Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

 📦 Steps Performed
1. Loaded and explored the dataset
2. Checked for missing values and encoded categorical variables
3. Selected features and target variable for regression
4. Split the data into training and testing sets
5. Built a linear regression model using `sklearn`
6. Evaluated the model using MAE, MSE, and R² Score
7. Plotted the regression line for visualization
8. Interpreted the model’s intercept and slope

 📉 Model Evaluation
- **MAE (Mean Absolute Error)**: Evaluates average magnitude of errors
- **MSE (Mean Squared Error)**: Penalizes larger errors
- **R² Score**: Indicates how well the model explains target variability

 📈 Interpretation
- The slope (coefficient) explains how much the price increases for each unit of area
- The intercept indicates the expected price when area is 0

 ✅ Conclusion
This task focused on applying simple linear regression to predict housing prices using one independent variable. The results and visualizations provided a basic understanding of regression modeling and interpretation using real-world data.
