 House Price Prediction - Machine Learning Notebook

 Project Overview

This notebook presents a complete Machine Learning workflow for predicting house prices using regression models.

The goal is to estimate the target variable (MEDV - Median House Value) based on multiple housing features.

 📊 Dataset

The dataset is based on a housing dataset similar to the Boston Housing dataset.

* Number of samples: ~500
* Number of features: 13
* Target: `MEDV` (house price)

Features include:

* CRIM → crime rate
* RM → average number of rooms
* LSTAT → % lower status population
* PTRATIO → pupil-teacher ratio
* TAX, INDUS, AGE, DIS, etc.


⚙️ Workflow in This Notebook

 1. Data Loading

* Loaded dataset from CSV file
* Fixed formatting issue (space-separated values)
* Assigned correct column names


 2. Data Preprocessing

* Checked dataset structure
* Removed outliers using IQR method
* Split data into features (X) and target (y)

 3. Exploratory Data Analysis (EDA)

* Histograms to analyze distributions
* Scatter plots (e.g., RM vs MEDV)
* Correlation heatmap to identify important features
* Boxplots to detect outliers

 4. Feature Engineering

* Selected important features based on correlation
* Removed weak or less relevant features

 Models Implemented
 🔹 Linear Regression

* Baseline regression model
* Simple and interpretable

🔹 K-Nearest Neighbors (KNN)

* Applied StandardScaler
* Tuned number of neighbors

🔹 Decision Tree Regressor

* Handles non-linear relationships

 🔹 Random Forest Regressor

* Ensemble model for improved performance

🔹 XGBoost Regressor 

* Advanced boosting algorithm
* Tuned hyperparameters

 🔹 XGBRFRegressor

* Random Forest variant of XGBoost


 📈 Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

 📊 Results

| Model             | R² Score  |
| ----------------- | --------- |
| Linear Regression | ~0.63     |
| KNN               | ~0.70     |
| Random Forest     | ~0.85     |
| XGBoost           | 🔥 ~0.80+ |


## 🚀 Key Improvements

* Removed outliers → improved performance
* Applied scaling for KNN
* Performed feature selection
* Tuned hyperparameters using GridSearch


 Key Learnings

* Outliers significantly affect regression performance
* Feature selection improves model accuracy
* Ensemble models outperform basic models
* Hyperparameter tuning is critical


 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn
* XGBoost

▶️ How to Run

1. Clone the repository
2. Install dependencies:
install -r requirements.txt
   ```
3. Open the notebook:


 Future Improvements

* Apply RandomizedSearchCV for faster tuning
* Try Gradient Boosting and LightGBM
* Deploy the model using FastAPI
 Author

Machine Learning Engineer in progress 
Focused on building strong ML projects and improving performance.

