# 📊 Predicting Term Deposit Subscriptions – A Machine Learning Approach  
**Capstone Project | Data Science Intern – Teachnook | May 2024**  
**Author:** Vinnakota Nitish Raj | `nvinnako2@gitam.in`

---

## 🔍 Project Overview

This capstone project dives deep into **predicting customer responses** to marketing campaigns run by a Portuguese banking institution. The objective is to determine whether a customer will subscribe to a **term deposit** based on a variety of socio-economic and campaign-related features.

Using real-world marketing data and a rigorous machine learning pipeline, this project showcases my **end-to-end data science capabilities** – from preprocessing, EDA, and feature engineering to model building, evaluation, and optimization.

---

## 🎯 Problem Statement

The bank wants to **maximize the efficiency** of its telemarketing campaigns. By building a predictive model that classifies whether a customer will subscribe to a term deposit (target: `yes` or `no`), they can significantly reduce costs, increase success rates, and personalize strategies.

---

## 📁 Dataset Summary

- **Source:** UCI Bank Marketing Dataset  
- **Records:** 45,211  
- **Features:** 16 input variables including `age`, `job`, `marital`, `education`, `balance`, `day`, `duration`, `pdays`, `previous`, etc.  
- **Target:** `y` – whether the client subscribed to a term deposit (`yes`/`no`)

---

## 🔬 Exploratory Data Analysis (EDA)

✅ Handled missing values, outliers, and categorical encoding  
✅ Visualized distributions using histograms, box plots, and correlation heatmaps  
✅ Derived insights like:
- Duration of call is a strong predictor
- Certain jobs and age groups are more likely to subscribe
- Campaign success increases with fewer previous contacts

---

## 🧠 Machine Learning Models

Built and compared **five+ powerful classifiers** to detect the best-performing model:

| Model                     | Evaluation Metric |
|--------------------------|------------------|
| Decision Tree Classifier | ✅ Accuracy, Precision, Recall, F1-Score |
| Random Forest Classifier | ✅ High recall and precision |
| Gradient Boosting        | ✅ Robust against overfitting |
| AdaBoost                 | ✅ Enhanced weak learners |
| Bagging Classifier       | ✅ Reduced variance |

📌 **Evaluation Techniques:**
- Train/Test split and Cross-validation (KFold)
- Confusion Matrix & Classification Report
- Accuracy, Precision, Recall, F1-score

---

## 🏆 Key Achievements

✅ Built a highly interpretable classification pipeline  
✅ Applied ensemble techniques to improve prediction accuracy  
✅ Highlighted business-impacting features for strategic decision-making  
✅ Delivered a clean, modular notebook with visual storytelling

---

## 📌 Skills Highlighted

`Pandas` • `Seaborn` • `Matplotlib` • `Scikit-Learn` • `EDA` • `Classification Models` • `Ensemble Learning` • `K-Fold Cross Validation` • `Model Evaluation` • `Real-world Data Preprocessing`

---

## 📈 Results

Among all models, **Random Forest and Gradient Boosting** achieved the best balance of accuracy and recall, making them ideal for business deployment where **false negatives (missed customers)** are costly.

---

## 🚀 Future Work

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV  
- Model explainability using SHAP or LIME  
- Deployment via Streamlit or Flask for real-time predictions  
- Cost-sensitive learning to handle business priorities

---

## 📮 Contact

For any queries or collaboration opportunities, feel free to connect!

**📧 Email:** nvinnako2@gitam.in  
**🔗 LinkedIn:** [Your LinkedIn Profile Link]  
**🌐 Portfolio:** [Your Portfolio Link]

---

> *“This project reflects my commitment to building data-driven, scalable, and impactful solutions using machine learning.”*
