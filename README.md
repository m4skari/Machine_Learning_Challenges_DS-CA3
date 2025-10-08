# Machine Learning Challenges – DS-CA3

This repository contains three end-to-end **machine learning projects** designed to address distinct real-world problems: classification, regression, and recommendation.  
All tasks were implemented as part of the *Introduction to Data Science* course (University of Tehran) and hosted on Kaggle for competitive evaluation.

---

## 🧠 Overview
The project is divided into three main tasks:

### 1️⃣ Cancer Survival Prediction (Classification)
- **Goal:** Predict whether a cancer patient is alive or deceased (`Survival_Status` = 1 or 0).  
- **Key Features:** Demographic, diagnostic, and treatment data (e.g., stage, therapy type, recurrence, smoking history).  
- **Approach:**  
  - Data cleaning, encoding categorical variables, scaling numerical values.  
  - Compared multiple models (Logistic Regression, SVM, Decision Tree, Random Forest).  
  - Evaluated using *Accuracy*, *Precision*, *Recall*, and *F1-Score*.  
- **Output:** CSV file with `id` and predicted `label`.

---

### 2️⃣ Bike Rental Demand Prediction (Regression)
- **Goal:** Predict total daily bike rentals (`total_users`) using environmental and temporal features.  
- **Techniques:**  
  - Feature selection via correlation analysis and p-value filtering.  
  - Regression algorithms tested: Linear Regression, Random Forest, Gradient Boosting.  
  - Metrics used: *RMSE*, *MAE*, *R²*, *MAPE*.  
  - Optional external data enrichment (holidays, weather events).  
- **Output:** CSV file with predicted rental counts per day.

---

### 3️⃣ Movie Recommendation System (Recommender)
- **Goal:** Predict unseen user–movie ratings using traditional ML algorithms (no deep learning).  
- **Data:**  
  - User–movie ratings (`train_data_movie_rate.csv`)  
  - Trust relationships (`train_data_movie_trust.csv`)  
- **Approach:**  
  - Preprocessed and normalized rating data.  
  - Integrated trust scores as additional features.  
  - Evaluated with *RMSE*, *MAE*, *MSE*, and *R²*.  
- **Output:** Predicted ratings for each `(user_id, item_id)` pair.

---

## ⚙️ Tools and Libraries
| Category | Tools |
|-----------|-------|
| ML Frameworks | scikit-learn, XGBoost, LightGBM, CatBoost |
| Data Processing | pandas, numpy, scipy |
| Visualization | matplotlib, seaborn |
| Evaluation | scikit-learn metrics |
| Environment | Python 3.x, Kaggle Notebooks |

---

## 📊 Evaluation
- Classification task → **Accuracy**
- Regression task → **MSE / RMSE**
- Recommendation task → **RMSE / MAE**
- Final grades combined Kaggle leaderboard (40%) + project code quality (60%)

---

## 🚀 Key Skills Demonstrated
- Data preprocessing and feature engineering  
- Model development and hyperparameter tuning  
- Statistical validation and metric analysis  
- Kaggle submission workflow and reproducibility  
- Recommender system design with trust-based filtering  

---

## 👤 Author
**Mohammad Askari**  
📧 [mohammadeaskary@gmail.com](mailto:mohammadeaskary@gmail.com)  
🌐 [GitHub – m4skari](https://github.com/m4skari)

