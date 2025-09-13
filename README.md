Soccer Match Outcome Predictor ⚽  

A machine learning project that predicts football match outcomes using historical Premier League data. The project applies feature engineering techniques such as rolling averages to capture recent team performance trends, and trains a **Random Forest Classifier** with **scikit-learn**, achieving **67.5% precision** on confident match outcome predictions.  

---

## 📌 Features  
- **Data Preprocessing** with `pandas`  
  - Converted categorical variables (venues, opponents) into numerical codes  
  - Extracted time-based features (match hour, day of week)  
  - Normalized inconsistent team names (e.g., “Wolverhampton Wanderers” → “Wolves”) 

- **Feature Engineering**  
  - Computed **rolling averages** for goals, shots, and other performance metrics  

- **Machine Learning**  
  - Built and trained a **Random Forest Classifier** (`scikit-learn`)  
  - Chronologically split data into **training (pre-2022)** and **testing (post-2022)** to avoid data leakage  
  - Achieved **67.5% precision** when predicting confident win/loss outcomes  

- **Evaluation & Analysis**  
  - Used `precision_score` and `crosstab` analysis to measure performance  
  - Compared predicted vs. actual outcomes to identify strengths and weaknesses  


## 🛠 Tech Stack  
- **Python**  
- **pandas** for data manipulation  
- **scikit-learn** (`RandomForestClassifier`, metrics)  


## 📊 Results  
- Achieved **67.5% precision** in confident win/loss predictions  
- Model highlights potential for applying ML to sports analytics, with opportunities for improvement through hyperparameter tuning and advanced feature engineering  


## 🚀 How to Run  
1. Clone this repository
3. Run the code file in Jupyter Lab
