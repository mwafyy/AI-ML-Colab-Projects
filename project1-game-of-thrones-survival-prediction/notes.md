🐉 Game of Thrones Survival Prediction  
📌 Project Overview  
This project aims to predict whether a Game of Thrones character will survive or not based on features from the **character-predictions.csv** dataset (Kaggle).  
The dataset contains attributes such as house affiliation, title, culture, and other numerical/categorical features that may influence the prediction.  

🎯 Objectives  
- Clean and preprocess the dataset for machine learning.  
- Perform in-depth Exploratory Data Analysis (EDA).  
- Engineer meaningful features to improve model accuracy.  
- Build and evaluate multiple classification models.  
- Select the best-performing model based on evaluation metrics.  

📊 Steps & Methodology  

**1. Data Cleaning**  
- Removed irrelevant columns and kept useful identifiers for reference.  
- Handled missing values (fill/drop/impute depending on the column).  
- Encoded categorical variables using Label Encoding / One-Hot Encoding.  

**2. Exploratory Data Analysis (EDA)**  
- Checked class balance for survival vs. non-survival.  
- Correlation heatmaps and distribution plots for key features.  
- Identified patterns (e.g., some houses/cultures had lower survival rates).  

**3. Feature Engineering**  
- Created indicators for nobility, titles, and house importance.  
- Extracted features like `Is_Main_House` and `Has_Title`.  
- Scaled numerical features using `StandardScaler` where appropriate.  

**4. Model Building**  
- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  
- **Random Forest Classifier**  
- **Support Vector Classifier (SVC)**  
- **XGBoost (XGBClassifier)**  
- **Artificial Neural Network (ANN)**

**5. Evaluation**  
- Metrics used: Accuracy, Precision, Recall, F1-score.  
- Visualized confusion matrices to inspect false positives/negatives.  
- Compared models before and after feature engineering and tuning.  

🛠 Tools & Libraries  
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  
- **XGBoost**  
- **TensorFlow / Keras**  

📌 Results & Insights  
- **Model performance (summary):**  
  - Logistic Regression, Random Forest, **SVC**, XGBoost, and ANN achieved **F1-score = 1.0**.  
  - K-Nearest Neighbors (KNN) achieved **F1-score > 90%**.  
- Feature engineering and preprocessing had a strong positive impact on all models.  
- Certain houses and titles are strong predictors of survival.  

**⚠️ Note / Caution:****  
Perfect F1 (1.0) for multiple models can indicate either excellent separability or potential issues such as overfitting or data leakage. Recommended checks:  
- Validate using cross-validation and a held-out test set.  
- Verify there is no target leakage (features derived from the target).  
- Try stratified CV and report averaged metrics.  

📂 Files  
- `game-of-thrones-survival.ipynb` → Main notebook containing all processing, analysis, and modeling steps.  
- `notes.md` → This description file.  

✍ Author  
Mohamed Elmwafy

