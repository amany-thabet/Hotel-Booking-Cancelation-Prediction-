# Hotel-Booking-Cancelation-Prediction-
Machine Learning pattern recognition project for predicting hotel booking cancellations using classification algorithms and data analysis.
Project Overview

This project applies Machine Learning and Pattern Recognition techniques to predict whether a hotel booking will be canceled or not.
The analysis is based on the Hotel Booking Demand dataset and focuses on data preprocessing, exploratory data analysis, feature engineering, feature selection, and classification model comparison.

The goal of the project is to help hotels reduce revenue loss and improve booking management by identifying cancellation patterns.

🎯 Objectives
Clean and preprocess hotel booking data
Explore booking behavior and cancellation patterns
Build and compare multiple classification models
Evaluate models using different performance metrics
Select the best-performing model
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
📂 Dataset

Dataset used: Hotel Booking Demand Dataset

Features include:

Lead time
Meal type
Market segment
Distribution channel
ADR (Average Daily Rate)
Customer type
Special requests
Reservation details

Target variable:

is_canceled
0 → Not Canceled
1 → Canceled
⚙️ Project Workflow
1. Data Cleaning
Handling missing values
Removing duplicates
Removing outliers
Dropping irrelevant columns
2. Exploratory Data Analysis (EDA)
Booking distribution analysis
Cancellation analysis
Lead time analysis
ADR analysis
Correlation analysis
3. Feature Engineering

Created new features such as:

total_people
total_stay
4. Data Preprocessing
Encoding categorical variables
Feature scaling using RobustScaler
5. Feature Selection

Used:

SelectKBest
ANOVA (f_classif)
6. Machine Learning Models

The following supervised classification models were implemented:

Logistic Regression
Decision Tree
Random Forest
📊 Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
🏆 Results

Random Forest achieved the best overall performance compared to other models.

Key findings:

Lead time strongly affects cancellation probability
Deposit type is highly related to cancellations
Random Forest provided the highest accuracy and F1-score
📈 Future Improvements
Apply hyperparameter tuning
Use cross-validation
Test additional models such as XGBoost
Handle class imbalance using SMOTE
