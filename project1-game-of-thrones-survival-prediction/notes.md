🐉 Game of Thrones Survival Prediction

📌 Project Overview
This project focuses on analyzing and building machine learning models to predict a target variable using extensive feature engineering, data preprocessing, and model evaluation techniques.
The dataset underwent cleaning, transformation, and advanced feature engineering to enhance model performance.

🔹 Feature Engineering & Data Preparation
Data Cleaning: Removed missing and irrelevant values.

Feature Scaling: Applied StandardScaler to normalize numerical features.

Encoding: Converted categorical variables into numerical format.

Feature Engineering:

Created new derived features to improve prediction capability.

Removed low-importance and redundant features after correlation analysis.

Used dimensionality reduction techniques where appropriate.

Data Splitting: Train-test split for robust model evaluation.

🤖 Machine Learning Models & Results
Multiple models were trained and evaluated using accuracy and F1-score as performance metrics.

Model	Accuracy	F1-Score
Random Forest	100%	1.00
Decision Tree	100%	1.00
Logistic Regression	100%	1.00
SVC (Support Vector Classifier)	100%	1.00
Gradient Boosting	100%	1.00
K-Nearest Neighbors (KNN)	~95%+	>0.90

✅ Observation:

All models except KNN achieved a perfect F1-score of 1.00.

KNN still performed exceptionally well with accuracy above 90% and F1-score above 0.90.

Feature engineering significantly improved model performance.

📊 Conclusion
High performance across models indicates excellent feature preparation and data quality.

Perfect F1-scores for most models demonstrate strong predictive capability and balanced precision-recall.

KNN performance suggests that distance-based methods may be slightly less suited for this dataset, but still viable.

Feature engineering played a key role in achieving these results.

📁 This project showcases effective preprocessing, feature engineering, and machine learning model building, with exceptional results across multiple algorithms.

