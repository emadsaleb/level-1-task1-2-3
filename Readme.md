 Iris Species Classification (Machine Learning Project)

 Overview

This project focuses on classifying iris flowers into three different species using Machine Learning models.
The goal is to predict the species of a flowerbased on its physical measurements.



📊 Dataset

The dataset used is the famous Iris Dataset.

* Number of samples: 150
* Number of features: 4
* Target: `species`

 Features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

 Classes:

* Setosa
* Versicolor
* Virginica



 Workflow

1. Data Preprocessing

* Loaded dataset from CSV
* Checked data structure and cleaned it
* Encoded target variable using LabelEncoder
* Verified dataset balance



 2. Exploratory Data Analysis (EDA)

* Visualized feature distributions
* Used scatter plots to understand relationships
* Observed strong separability between classes



3. Feature Engineering

* Selected all features (small dataset)
* No missing values handling required



 Models Implemented

🔹 Logistic Regression

* Baseline classification model
* Fast and interpretable

 🔹 K-Nearest Neighbors (KNN)

* Applied feature scaling using StandardScaler
* Tuned number of neighbors



 📈 Model Evaluation

Metrics used:

* Accuracy Score
* Classification Report
* Confusion Matrix



📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~95%     |
| KNN                 | ~95%+    |

 Key Insights

* The dataset is clean and balanced
* KNN performs very well after scaling
* Features are highly separable → high accuracy



 Key Learnings

* Importance of feature scaling in KNN
* Difference between classification metrics
* Understanding model performance using confusion matrix



 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn
 Future Work

* Try SVM and Decision Tree
* Deploy model using API
* Build a simple UI for predictions



 Author

Machine Learning Enthusiast
Focused on improving ML skills and building real-world projects.


