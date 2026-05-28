🏠 House Price Prediction using Regression & Tree-Based Models

📌 Project Overview

This project focuses on House Price Prediction using different Machine Learning Regression Algorithms. The goal is to analyze housing data and compare multiple models to find which algorithm predicts house prices most accurately.

The project includes data preprocessing, feature selection, model training, hyperparameter tuning, and performance evaluation.

🎯 Objectives Load and understand housing dataset Perform data preprocessing Select important house-related features Apply and compare multiple ML algorithms Evaluate model performance using error metrics Visualize Decision Tree and Random Forest trees 📂 Dataset Features

The dataset contains housing-related information such as:

area_sqft → House area in square feet bedrooms → Number of bedrooms bathrooms → Number of bathrooms location_score → Location quality score property_age → Property age distance_city_km → Distance from city near_school → Nearby school availability near_metro → Nearby metro availability crime_rate_index → Crime rate score house_price_inr → Target variable (House Price) ⚙️ Technologies Used

This project is built using:

Python Pandas → Data handling NumPy → Numerical operations Matplotlib & Seaborn → Data visualization Scikit-learn → Machine Learning models 🤖 Machine Learning Models Used

The following algorithms are implemented and compared:

Linear Regression
Basic regression model used as a baseline.

Ridge Regression
Regularization technique that reduces overfitting using L2 penalty.

Lasso Regression
Regularization technique using L1 penalty which can reduce less important feature coefficients.

Decision Tree Regressor
Tree-based model used to predict house prices and visualize decision-making.

Random Forest Regressor
Ensemble learning method that combines multiple decision trees for better prediction accuracy.

Support Vector Regression (SVR)
Regression technique that works well with complex data relationships.

🔧 Project Workflow Step 1: Import Libraries

Required Python libraries are imported.

Step 2: Load Dataset

Housing dataset is loaded using Pandas.

Step 3: Data Exploration

The project checks:

Dataset shape Data types Missing values Statistical summary Sample records Step 4: Feature Selection

Input variables (X) and target variable (y) are selected.

Step 5: Data Splitting & Scaling Train-Test split performed StandardScaler used for normalization Step 6: Model Training

Different ML models are trained.

Step 7: Hyperparameter Tuning

GridSearchCV is used to find the best alpha values for:

Ridge Regression Lasso Regression Step 8: Model Evaluation

Models are evaluated using:

MSE (Mean Squared Error) MAE (Mean Absolute Error) RMSE (Root Mean Squared Error) R² Score Step 9: Tree Visualization

Decision Tree and Random Forest trees are visualized for better understanding.

📊 Results

A comparison table is created to compare all models based on:

✔ MSE ✔ MAE ✔ RMSE ✔ R² Score

This helps identify the best-performing model.

📷 Output Highlights Ridge vs Lasso comparison Decision Tree visualization Controlled Decision Tree visualization Random Forest tree visualization Final model performance comparison table 🚀 Future Improvements

Possible improvements:

Use larger real-world datasets Perform feature engineering Deploy model using Flask/Streamlit Improve accuracy using advanced ensemble methods

👩‍💻 Author

Purvi Talaviya
